FROM nginx
RUN adduser --system --user-group raja
RUN echo "Hello" > /tmp/hello.txt
RUN chown -R raja:raja /tmp
CMD [ "nginx" , "-g" , "daemon off;" ]
USER raja


# FROM busybox:stable
# CMD ["sh"]