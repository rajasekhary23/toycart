FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
# RUN useradd nginx1
# USER nginx1
RUN echo "Hello" > /tmp/hello.txt
CMD [ "nginx" , "-g" , "daemon off;" ]