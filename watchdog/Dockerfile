FROM --platform=linux/arm64 ubuntu:21.04
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update
RUN apt-get install -y watchdog
RUN apt-get install -y netbase
COPY scripts /scripts

ENTRYPOINT /scripts/startup.sh
