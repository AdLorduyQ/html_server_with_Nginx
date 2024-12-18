## Usage Guide

Create an image from the Dockerfile using the command:

```bash
docker build -t imagename .
```
Then, creat a container from the image and ran it. You can use the following command for both actions:

```bash
docker run -d -p 80:80 --name containername imagename
```

(Port 80 is used by default. If it is already in use, change the output port, the first port.)

Navigate to localhost:portnumber or simply localhost if you left it at port 80, and verify that the page is running.


Let me know if you need further changes!
