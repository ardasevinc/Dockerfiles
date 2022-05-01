FROM ubuntu:20.04

RUN apt update && apt-get install -y ca-certificates python3-pip curl

RUN pip3 install apt-mirror-updater

RUN apt-mirror-updater -c http://ubuntu.vargonen.com/ubuntu/