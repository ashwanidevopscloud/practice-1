FROM nginx
RUN rm -rf /usr/share/nginx/html/*
WORKDIR /usr/share/nginx/html
RUN pwd
COPY code .
RUN rm -f /etc/nginx/nginx.conf
COPY expense.conf /etc/nginx/default.d/expense.conf
COPY nginx.conf /etc/nginx/nginx.conf

