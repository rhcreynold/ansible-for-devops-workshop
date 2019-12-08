FROM rhscl/httpd-24-rhel7
USER root
MAINTAINER creynold@redhat.com
ADD httpd.conf /etc/httpd/conf
ADD index.html /var/www/html/
RUN chown -R apache:apache /var/www/html
EXPOSE 8080
