# pwn_docker
---
- Dockerfile for pwn
```
docker build --tag {imagename}:{tagnum} .
docker run -it --name 18.04 -v $PWD/{shareddir}:/{containerdir} {imagename:tagnum} usr/bin/zsh
```
