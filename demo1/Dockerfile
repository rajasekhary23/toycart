FROM alpine:latest
# RUN addgroup -S nginx1 && adduser -S nginx1 nginx1
RUN apk update \
     && apk add nginx
RUN adduser -S -D -g 'myuser' myuser \
     && mkdir /myuser
ADD nginx.conf /etc/nginx/nginx.conf.orig \
     && index.html /myuser/
CMD [ "nginx", "start" ]
# CMD ["sleep","2000"]


# FROM nginx
# RUN addgroup nginx1 && useradd nginx1 nginx1
# RUN echo "Hello" > /tmp/hello.txt
# # Run chown -R nginx1:nginx1 /opt
# CMD [ "nginx" , "-g" , "daemon off;" ]
# USER nginx1


# FROM busybox:stable
# CMD ["sh"]