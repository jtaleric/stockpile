FROM centos/tools
USER root
RUN rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
RUN yum install dmidecode
RUN git clone https://github.com/redhat-performance/stockpile /opt/stockpile
