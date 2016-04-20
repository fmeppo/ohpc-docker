FROM centos:7.2.1511
MAINTAINER Mike Shuey "shuey@fmepnet.org"

ENV OHPC_RELEASE=1.1 \
    OHPC_PKG_VERSION=1.1-1

RUN yum install -y epel-release && \
    rpm -ivh http://build.openhpc.community/OpenHPC:/${OHPC_RELEASE}/CentOS_7.2/x86_64/ohpc-release-${OHPC_PKG_VERSION}.x86_64.rpm

ENTRYPOINT /bin/bash
