FROM mysql:5.7
#set up database name and root pass
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"
#add dump data
COPY ./db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
EXPOSE 3306 33060
CMD ["mysqld"]
    
