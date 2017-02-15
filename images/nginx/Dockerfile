FROM nginx:alpine

MAINTAINER Ed Zynda <ezynda3@gmail.com>

RUN rm -f /etc/nginx/conf.d/default.conf\
    && echo "daemon off;" >> /etc/nginx/nginx.conf

ADD default /etc/nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx"]