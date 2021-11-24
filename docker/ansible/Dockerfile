FROM centos:latest

ENV ANSIBLE_HOST_KEY_CHECKING False

RUN yum update -y && \
    yum install -y epel-release

RUN yum install -y ansible openssh-clients

CMD /bin/bash
