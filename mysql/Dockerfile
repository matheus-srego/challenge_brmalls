FROM mysql:8.0
USER root

ENV MYSQL_USER=xpto_user
ENV MYSQL_PASSWORD=qwerty
ENV MYSQL_ROOT_PASSWORD=Qwert123@

COPY ./queries /docker-entrypoint-initdb.d

EXPOSE 3306
