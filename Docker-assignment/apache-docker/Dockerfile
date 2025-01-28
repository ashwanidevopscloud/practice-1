FROM almalinux
RUN mkdir /apache_docker_project
WORKDIR /apache_docker_project
COPY index.html /apache_docker_project
EXPOSE 80
RUN apt install –y apache2 
RUN apt install –y apache2-utils 
RUN apt clean 
CMD ["apachectl", "-D", "FOREGROUND"]
