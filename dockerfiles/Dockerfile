FROM centos:latest
MAINTAINER pyama86 <www.kazu.com@gmail.com>
RUN yum install -y sudo
RUN curl -fsSL https://repo.stns.jp/scripts/yum-repo.sh | sh
RUN yum install -q -y glibc gcc make libcurl-devel wget bzip2 git vim epel-release clang stns-v2 initscripts nc
RUN mkdir /stns
WORKDIR /stns
