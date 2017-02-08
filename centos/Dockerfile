FROM centos:7.2.1511

MAINTAINER Jim Holmstrom <jim.holmstroem@gmail.com>

RUN yum install -y make tar unzip gcc gcc-devel openssl-devel readline-devel && yum clean all

ARG LUAJIT_VERSION

RUN curl -L http://luajit.org/download/LuaJIT-${LUAJIT_VERSION}.tar.gz | tar zx && \
    cd /LuaJIT-${LUAJIT_VERSION} && \
    make && \
    make install && \
    cd .. && rm /LuaJIT-${LUAJIT_VERSION} -rf

ENTRYPOINT [ "/usr/bin/env", "luajit" ]
