FROM postgres

COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432

# docker run --name some-postgres -e POSTGRES_PASSWORD=Pp123456789 -d postgres