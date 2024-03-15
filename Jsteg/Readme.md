## Jsteg is a package for hiding data inside JPEG files with a technique known as steganography. This is accomplished by copying each bit of the data into the least-significant bits (LSB) of the image. The amount of data that can be hidden depends on the file size of the jpeg; it takes about 10-14 bytes of jpeg to store each byte of the hidden data.

## Installation of jsteg-

`sudo wget -O /usr/bin/jsteg https://github.com/lukechampine/jsteg/releases/download/v0.1.0/jsteg-linux-amd64`

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/160a9781-f4cb-462f-9fcb-3db44e5b0823)

`sudo chmod +x /usr/bin/jsteg`

> We will make jsteg executable

`sudo wget -O /usr/bin/slink https://github.com/lukechampine/jsteg/releases/download/v0.2.0/slink-linux-amd64`

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/1594b652-3695-494a-bfda-92740ccfdc67)

Download an image of any format and store it in the current directory test.jpg

And Create a sample txt file which contains the secret message which is to be embeded with the image.

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/ceb0d714-670c-4cd5-8640-8e80e7131404)

Commands to embed a file in the JPEG image is as follows.
`jsteg hide <in.jpg> <secret file name> <out.jpg>`

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/f9d594da-3680-40cb-83ff-c6aef1ef5f16)

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/8337ba06-2d8b-445b-9db8-678e3f162212)

> We can see that out.jpg file is created now we will extract the hidden message.

Revealing data
The syntax for revealing data is as follows.

`jsteg reveal <in.jpg> <output file name>`

![image](https://github.com/anandurdas11/StegnoGraphy/assets/83402050/56a2f7c3-b555-4c15-8c5f-a7db1798cbc7)

Decoded 


