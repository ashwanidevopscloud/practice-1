FROM ub
# RUN rm -rf /var/www/html
WORKDIR /var/www/html
RUN pwd
COPY . /var/www/html
EXPOSE 80
RUN apt-get update
RUN apt install -y apache2 
RUN apt clean 
CMD ["apache2ctl", "-D", "FOREGROUND"]
