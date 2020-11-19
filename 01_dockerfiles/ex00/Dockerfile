FROM alpine

MAINTAINER kgomera <kgomera@student.wethinkcode.co.za>

RUN apk update && \
    apk upgrade && \
    apk add emacs

ENTRYPOINT emacs

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -ti ex00
