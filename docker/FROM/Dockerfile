FROM almalinux
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
# CMD ["echo", "hello-world"]
LABEL author="ashwaani" \
      course="devops" \
      topic="aws" 

COPY index.html /usr/share/nginx/html/about.html
COPY home.html /usr/share/nginx/html/home.html
ADD  https://raw.githubusercontent.com/daws-81s/concepts/refs/heads/main/self-intro.yaml /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]