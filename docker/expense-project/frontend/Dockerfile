FROM nginx
RUN rm -rf /usr/share/nginx/html/*
WORKDIR /usr/share/nginx/html
RUN pwd
COPY code .
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d
COPY expense.conf /etc/nginx/default.d/expense.conf
COPY nginx.conf /etc/nginx/nginx.conf