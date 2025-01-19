FROM almalinux
RUN dnf install nginx -y
# CMD ["echo", "hello-world"]
LABEL author="ashwaani" \
      course="devops" \
      topic="aws" \


COPY ./FROM /user/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon-off"]
ADD https://www.resume.com/ /usr/share/nginx/html/index.html
# RUN chmod+X /user/share/nginx/html/index.html