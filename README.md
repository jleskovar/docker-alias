# Docker 

Fork of tcnksm/docker-alias, modulo zsh support (although it may work out of the box)

## Pre-requisites
Make sure the official [Docker bash completions](https://raw.githubusercontent.com/docker/docker/master/contrib/completion/bash/docker) are installed 

## Install
```bash
$ curl -fsSL https://raw.github.com/jleskovar/docker-alias/master/docker_functions >> ~/.bashrc && source ~/.bashrc
```

## Commands

    # Get latest container ID
    dl

    # Get container process
    dps

    # Get process included stop container
    dpa

    # Get images
    di

    # Get container IP
    dip

    # Run deamonized container, e.g., $dkd base /bin/echo hello
    dkd

    # Run interactive container, e.g., $dki base /bin/bash
    dki

    # Stop all containers
    dstop

    # Remove all containers
    drm

    # Stop and Remove all containers
    dsr

    # Remove all images
    dri

    # Dockerfile build, e.g., $dbu tcnksm/test 
    dbu

    # Run bash for any image
    dbash

    # Enter docker container
    dent

    # Find out container PID
    dpid

    # Get stats for a container
    ds


## Reference

- [Useful Docker Bash functions and aliases](http://www.kartar.net/2014/03/some-useful-docker-bash-functions-and-aliases/)
- [15 QUICK DOCKER TIPS](http://www.centurylinklabs.com/15-quick-docker-tips/)
