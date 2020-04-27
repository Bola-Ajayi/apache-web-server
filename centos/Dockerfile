FROM centos:7
MAINTAINER bola.ajayi@gmail.com
USER root 
ENV container docker

RUN yum -y install httpd
# Add configuration file
RUN echo “My first Apache Web Server is Running By Bola” > /var/www/html/index.html

# Start the service
ENTRYPOINT ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80
