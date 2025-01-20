FROM nginx
RUN rm -rf /usr/share/nginx/html/*
WORKDIR /usr/share/nginx/html
RUN pwd
COPY code .
USER nginx
COPY expense.conf .

