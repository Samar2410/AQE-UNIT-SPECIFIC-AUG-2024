FROM ubuntu:18.04
RUN apt-get -y update && apt-get -y install nginx
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/nginx","-g","daemon off;"]

