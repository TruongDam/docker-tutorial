## Test Docker version
* Run docker --version and ensure that you have a supported version of Docker

```
docker --verion
Docker version 18.06.1-ce, build e68fc7a
```

* Run docker info to view more details

```
docker info 

Containers: 2
 Running: 0
 Paused: 0
 Stopped: 2
Images: 1
Server Version: 18.06.1-ce
Storage Driver: overlay2
 Backing Filesystem: extfs
Kernel Version: 4.4.0-36-generic
Operating System: Ubuntu 16.04 LTS
OSType: linux
Architecture: x86_64
CPUs: 4
Total Memory: 15.56GiB
...

```

## Test Docker installation
* List all image that was downloaded to your machince
```
docker image ls
```

* Execute Docker image 

```
docker run [docker-image]
docker run hello-world

Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
1b930d010525: Pull complete 
Digest: sha256:92695bc579f31df7a63da6922075d0666e565ceccad16b59c3374d2cf4e8e50e
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.
```


* List Docker containers (running, all, all in quiet mode)
```
docker container ls
docker container ls --all
docker container ls -aq
```
