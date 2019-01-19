FROM ubuntu:latest
MAINTAINER Tung Vo <thanhtungvl2510@gmail.com>

RUN apt-get -y update && \
    apt-get -y upgrade && \
    apt-get -y install software-properties-common && \
    apt-add-repository ppa:ansible/ansible && \
    apt-get -y update && \
    apt-get -y install ansible

COPY ansible /ansible
WORKDIR /ansible

CMD ["tail", "-f", "/dev/null"]