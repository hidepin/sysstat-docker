FROM centos:7

LABEL maintainer "Hidetoshi Imai <hidepin@gmail.com>"

RUN yum install -y sysstat
RUN ln -sf /usr/share/zoneinfo/Asia/Tokyo /etc/localtime
RUN mkdir -p /sysstat

WORKDIR /sysstat

CMD ["sar", "-h"]
