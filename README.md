## Docker Base: Unicorn


This repository contains **Dockerbase** of [Unicorn](http://unicorn.bogomips.org/) for [Docker](https://www.docker.com/)'s [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/unicorn/) published on the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Depends on:

* [dockerbase/devbase-rvm](https://registry.hub.docker.com/u/dockerbase/devbase-rvm)


### Installation

1. Install [Docker](https://docs.docker.com/installation/).

2. Download [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/unicorn/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerbase/unicorn`


### Usage

    docker run -it --rm --name dockerbase-unicorn dockerbase/unicorn

### Components & Versions

    Description:	Ubuntu 14.04.1 LTS
    git version 1.9.1
    OpenSSH_6.6.1p1 Ubuntu-2ubuntu2, OpenSSL 1.0.1f 6 Jan 2014
    GNU Make 3.81
    Copyright (C) 2006  Free Software Foundation, Inc.
    This is free software; see the source for copying conditions.
    There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A
    PARTICULAR PURPOSE.
    
    This program built for x86_64-pc-linux-gnu
    rvm 1.25.31 (stable) by Wayne E. Seguin <wayneeseguin@gmail.com>, Michal Papis <mpapis@gmail.com> [https://rvm.io/]
    ruby 2.1.2p95 (2014-05-08 revision 45877) [x86_64-linux]
    
    Rails 4.1.6
    unicorn v4.8.3
