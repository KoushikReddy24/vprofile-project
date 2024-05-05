FROM mysql:8.0.33

LABEL "Project"="Vprofile"
LABEL "Author"="KoushikRedddy24"

ENV MYSQL_ROOT_PASSWORD="admin@123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
