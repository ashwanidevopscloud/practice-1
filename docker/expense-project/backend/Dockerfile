FROM nodejs/devcontainer:20
EXPOSE 8080
RUN useradd expense
USER expense
RUN mkdir /app
WORKDIR /app
RUN pwd
copy *.js  /app
copy package.json  /app
copy schema/*.sql  /app
RUN npm install
ENV DB_HOST="mysql"
