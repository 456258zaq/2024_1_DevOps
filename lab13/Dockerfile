FROM centos:7
MAINTAINER Byunghoonlee
RUN yum -y install epel-release
RUN yum -y install httpd
EXPOSE 80 443
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]
