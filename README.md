# Overview

The toolkits for docker devops.

* Minmized images based on alpine image.
* Scripts to simplify docker backup & restore.


## Minmized images

[mini docker @ docker hub](https://hub.docker.com/u/clouthinkin/)

All based on the mini alpine image and add following supports:
* bash
* curl
* lsof

And the version is

IMAGE NAME | VERSION
---|---
clouthinkin/jdk | jdk 8
clouthinkin/jre | jre 8
clouthinkin/golang | golang 1.8.4
clouthinkin/node | node 8
clouthinkin/python | python 2.7
clouthinkin/nginx | nginx 1.13.7
clouthinkin/redis | redis 4.0.2 


### nginx + php 5 + mysql client

Please see [Guide](nginx-php5-server/README.md)


## Helpful scripts

* export mongodb 
* import mongodb
* export mysql
* import mysql

