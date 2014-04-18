nupic-docker
============

Dockerfile suitable for building numenta/nupic in [Docker](https://www.docker.io/).

Built and tested on Amazon Linux, but should work in CentOS.

Usage
-----

    git clone git://github.com/oxtopus/nupic-docker.git
    cd nupic-docker
    sudo docker build .
    sudo docker run -i -t $IMAGE /bin/bash    
