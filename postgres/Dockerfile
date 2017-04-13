FROM postgres
ENV POSTGRES_PASSWORD postgres
ENV PGDATA /var/lib/postgresql/data/pgdata_volume
COPY sql/*.sql /docker-entrypoint-initdb.d
