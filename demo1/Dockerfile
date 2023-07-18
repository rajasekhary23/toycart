FROM nginx
RUN addgroup -r nginx1 && useradd -r nginx1 nginx1
RUN echo "Hello" > /tmp/hello.txt
RUN chown -R nginx1:nginx1 /tmp
CMD [ "nginx" , "-g" , "daemon off;" ]
USER nginx1


# FROM busybox:stable
# CMD ["sh"]