# Dockerfile based on the latest CentOS 7 image - non-privileged user entry
FROM centos:latest
MAINTAINER linuxacademy@linuxacademy.com

RUN useradd -ms /bin/bash user

CMD "echo" "Hey! Non sentient custom container message.  You're doing great!"

USER user
