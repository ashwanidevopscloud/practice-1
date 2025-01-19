ARG version
FROM almalinux:9
RUN echo "my app version is ${version}"
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
# CMD ["echo", "hello-world"]
LABEL author="ashwaani" \
      course="devops" \
      topic="aws" 

COPY index.html /usr/share/nginx/html/about.html
COPY home.html /usr/share/nginx/html/home.html
ADD  https://raw.githubusercontent.com/daws-81s/concepts/refs/heads/main/self-intro.yaml /usr/share/nginx/html/index.html
RUN chmod +rx /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
ENV course="devops" \
    duration="2hours" \
    trainer="shiva"
RUN echo "course:$course, duration:$duration, trainer:$trainer"
ARG course="Frontend" \
    duration="5hours............................" \
    trainer="Skill up technologyies to #####################"
RUN echo "course:$course, duration:$duration, trainer:$trainer"