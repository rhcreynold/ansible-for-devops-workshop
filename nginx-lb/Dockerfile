FROM nginx
USER root
MAINTAINER creynold@redhat.com
RUN rm /etc/nginx/conf.d/default.conf
COPY ./etc/nginx/conf.d/nginx.conf /etc/nginx/conf.d/default.conf
