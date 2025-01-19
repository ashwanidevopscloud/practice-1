FROM almalinux
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
# CMD ["echo", "hello-world"]
LABEL author="ashwaani" \
      course="devops" \
      topic="aws" 

COPY index.html /usr/share/nginx/html/about.html
COPY home.html /usr/share/nginx/html/home.html
CMD ["nginx", "-g", "daemon off;"]
ADD https://www.resume.com/ /usr/share/nginx/html/index.html
RUN chmod+X /user/share/nginx/html/index.html