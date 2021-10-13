FROM mysql:5.6

ENV MYSQL_DATABASE=toystore

COPY ./*.sql /docker-entrypoint-initdb.d/
