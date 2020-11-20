# Derived from official mysql image (our base image)
FROM mysql:5.7
# Add a database
ENV MYSQL_DATABASE=flask_db
ENV ROOT_PASSW0RD=${ROOT_PASSWORD}
# Add the content of the .sql file to your image
ADD CreateTable.sql docker-entrypoint-initdb./
# All scripts in docker-entrypoint-initdb.d/ are automatically executed during container startup
