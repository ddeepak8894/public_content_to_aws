FROM mysql
ENV MYSQL_ROOT_PASSWORD "manager"
ENV MYSQL_DATABASE "sensor_data"
COPY sensor_data.sql /docker-entrypoint-initdb.d
COPY my.cnf /etc/mysql/my.cnf
EXPOSE 3306 