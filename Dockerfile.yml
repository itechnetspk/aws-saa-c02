FROM centos:latest
LABEL maintainer="iTechNets"
RUN yum -y install httpd
COPY index.html /var/www/html/
COPY itechnets*.jpg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80