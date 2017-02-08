FROM alpine:3.5

MAINTAINER Jim Holmstrom <jim.holmstroem@gmail.com>

ARG LUAJIT_VERSION

RUN apk add --no-cache luajit

ENTRYPOINT [ "/usr/bin/env", "luajit" ]
