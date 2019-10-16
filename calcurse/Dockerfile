FROM alpine:latest

RUN apk update && apk add calcurse
RUN mkdir -p /data
WORKDIR /data

ENTRYPOINT ["/usr/bin/calcurse", "-D", "/data"]