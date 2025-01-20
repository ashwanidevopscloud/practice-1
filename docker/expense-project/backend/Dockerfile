FROM node:20
EXPOSE 8080
RUN mkdir /app
WORKDIR /app
RUN pwd
COPY *.js  /app
COPY package.json  /app
COPY schema/*.sql  /app
RUN npm install
RUN useradd expense
USER expense
ENV DB_HOST="mysql"
