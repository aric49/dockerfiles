FROM ubuntu:18.04
MAINTAINER Aric Renzo - aricrenzo@gmail.com

RUN apt update && apt install -y hollywood byobu --no-install-recommends \
  && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["/usr/bin/hollywood"]
