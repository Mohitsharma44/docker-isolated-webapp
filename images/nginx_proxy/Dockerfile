FROM smebberson/alpine-nginx
MAINTAINER Mohit Sharma <mohitsharma44@gmail.com>

ADD root /

EXPOSE 80

RUN ln -sf /dev/stdout /var/log/nginx/access.log && \
    ln -sf /dev/stderr /var/log/nginx/error.log
