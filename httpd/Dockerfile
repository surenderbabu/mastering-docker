#InstllilngHttpd

# Base OS - Centos 

FROM ubuntu:trusty

# Install Httpd Package
RUN apt-get update -y && apt-get install -y apache2
 
# WORKINGDIR /var/www/html
WORKDIR /var/www/html/
# Copy index.html to /var/www/html/

COPY . . 

# Start the Service

CMD ["apachectl", "-D","FOREGROUND"]