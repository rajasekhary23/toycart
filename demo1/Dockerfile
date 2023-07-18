FROM nginx
RUN addgroup --system raja && adduser --system raja
RUN echo "Hello" > /tmp/hello.txt
RUN chown -R raja:raja /tmp
USER raja
CMD [ "nginx" , "-g" , "daemon off;" ]


# FROM busybox:stable
# CMD ["sh"]