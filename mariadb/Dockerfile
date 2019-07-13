FROM mariadb:5.5

LABEL maintainer="Goffity Corleone"

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d
COPY ./my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
