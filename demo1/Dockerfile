FROM centos
RUN yum update -y
RUN yum install nginx -y
RUN addgroup -s nginx1 && useradd -s nginx1 nginx1
RUN echo "Hello" > /tmp/hello.txt
# Run chown -R nginx1:nginx1 /opt
CMD [ "nginx" , "-g" , "daemon off;" ]
USER nginx1