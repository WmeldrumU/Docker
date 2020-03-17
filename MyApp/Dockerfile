FROM centos:7
RUN yum install httpd
COPY index.html /var/www/html
EXPOSE 80
CMD ["httpd", "-DFOREGROUND"]