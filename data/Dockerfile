FROM mysql:latest

COPY my.cnf /etc

COPY mysqld.cnf /etc/mysql/mysql.conf.d/

ENV MYSQL_ROOT_PASSWORD=root

ENV MYSQL_DATABASER=adaa_dev_new

ENV MYSQL_USER=adaa_deve_new

ENV MYSQL_PASSWORD=adaa_deve_new

COPY adaa_dev_new.sql /docker-entrypoint-initdb.d

EXPOSE 3306