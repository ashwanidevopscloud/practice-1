FROM almalinux
RUN dnf install nginx -y
CMD ["echo", "hello-world"]
LABEL author="ashwaani" \
      course="devops" \
      topic="aws" \


COPY index.html /user/share/nginx/html/index.html
ADD https://www.resume.com/ /usr/share/nginx/html/index.html
# RUN chmod+X /user/share/nginx/html/index.html