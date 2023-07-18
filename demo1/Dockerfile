FROM nginx
RUN addgroup -S nginx1 && useradd -S nginx1 nginx1
RUN echo "Hello" > /tmp/hello.txt
# Run chown -R nginx1:nginx1 /opt
CMD [ "nginx" , "-g" , "daemon off;" ]
USER nginx1