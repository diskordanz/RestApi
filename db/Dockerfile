FROM postgres:alpine

COPY ./db_init.sql /docker-entrypoint-initdb.d/db_init.sql

EXPOSE 5432
CMD ["postgres"]