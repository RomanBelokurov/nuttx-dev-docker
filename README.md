## Nuttx OS. Build in Docker.


### Clone Nuttx submodules
    
    git submodule update --init --recursive
    
### Install docker on your host system

see more information at official [docker installation](https://docs.docker.com/engine/install/) guide.

### Build and run docker image

#### Linu and MacOS:

To build docker image run:

    source docker-setup.sh build

To run docker container run:

    source docker-setup.sh run

#### Windows:

To build docker image run:

    .\docker-setup.bat build

To run docker container run:

    .\docker-setup.bat run


### Work in container
Have fun with development...
