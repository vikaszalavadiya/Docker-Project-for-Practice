FROM mysql:5.7.25
LABEL "Project"="vprofile"
LABEL "Author"="Vikas"
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD accountsdb.sql docker-entrypoint-initdb.d/accountsdb.sql
