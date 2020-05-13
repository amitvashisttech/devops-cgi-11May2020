# Base Image
FROM ubuntu:16.04

# Owner 
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update APT Repo
RUN apt-get update 

# Install Apache2 Packages 
RUN apt-get install apache2 -y 

# Custom Web Page
COPY amit.html /var/www/html/info.html

# Bring up the Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
