FROM nginx
RUN rm -rf /usr/share/nginx/html/*
WORKDIR /usr/share/nginx/html
COPY *.conf .
COPY code .
EXPOSE 80


