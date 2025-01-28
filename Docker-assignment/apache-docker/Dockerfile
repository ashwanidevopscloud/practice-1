FROM httpd:2.4
RUN rm -rf /var/www/html/*
WORKDIR /var/www/html
RUN pwd
COPY . /var/www/html
EXPOSE 80
RUN apt-get update
RUN apt install -y apache2 
RUN apt install -y apache2-utils 
RUN apt clean 
CMD ["apachectl", "-D", "FOREGROUND"]
