FROM ubuntu:jammy

RUN mkdir /tools
WORKDIR /tools

RUN apt-get update && apt-get install -y wget git gcc \
                                      bzip2 fontconfig

#ENTRYPOINT ["/scripts/mvn.sh"]
