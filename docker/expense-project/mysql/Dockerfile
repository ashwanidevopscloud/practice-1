FROM mysql:oraclelinux9
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1 
    # MYSQL_DATABASE=transcations \
    # MYSQL_USER=expense \
    # MYSQL_PASSWORD=ExpenseApp@1
COPY scripts/*.sql /docker-entrypoint-initdb.d

    