#UBUNTU-BASE
#
#VERSION 0.0.1

FROM ubuntu:14.04

MAINTAINER MrNull

RUN sudo apt-get update

RUN echo 'root:class100' | chpasswd
RUN mkdir /var/run/sshd
RUN sed -i 's/PermitRootLogin without-password/PermitRootLogin yes/' /etc/ssh/sshd_config

