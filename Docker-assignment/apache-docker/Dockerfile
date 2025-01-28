FROM almalinux
RUN mkdir /apache_docker_project
WORKDIR /apache_docker_project
copy index.html /apache_docker_project
Expose 80
RUN apt-get update && apt-get install -y apache2 && apt-get clean
CMD ["apachectl", "-D", "FOREGROUND"]
