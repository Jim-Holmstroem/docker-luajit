[![LuaJIT logo](https://github.com/Jim-Holmstroem/docker-luajit/blob/master/luajit.png?raw=true)](http://www.luajit.org/)

# Supported tags and respective ```Dockerfile``` links
* ```2.0.4```, ```2.0```, ```2```, ```latest``` [(latest/Dockerfile)](https://github.com/Jim-Holmstroem/docker-luajit/blob/master/centos/Dockerfile)
* ```alpine``` [(alpine/Dockerfile)](https://github.com/Jim-Holmstroem/docker-luajit/blob/master/alpine/Dockerfile)
    The alpine version just runs the latest beta LuaJIT.

# Docker hub link
* [jimho/luajit](https://hub.docker.com/r/jimho/luajit/)

# Build container
```
docker build --build-arg LUAJIT_VERSION=<version> -t luajit:<version> .
```
