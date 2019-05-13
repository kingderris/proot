FROM alpine:3.9

RUN apk update && apk add \
        bash \
        bsd-compat-headers \
        coreutils \
        grep \
        libarchive-dev \
        linux-headers \
        lzo \
        make \
        mcookie \
        musl-dev \
        python2-dev \
        swig \
        talloc-dev \
#        uthash-dev # only on testing

WORKDIR /usr/src/proot
COPY . /usr/src/proot
