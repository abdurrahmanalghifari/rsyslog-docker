FROM centos:7
MAINTAINER abdurrahmanalghifari.github.io

USER root
RUN cat /usr/share/zoneinfo/Asia/Jakarta > /etc/localtime
RUN yum -y update; yum -y install epel-release
RUN yum -y install ntpdate vim wget git gcc net-tools iproute openssh-clients openssh-server ntpdate geoip-devel pcre-devel zlib-developenssl openssl-devel rsyslog

