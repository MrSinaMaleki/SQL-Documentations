# SQL Commands Would be added here


4. PostgreSQL – Loading a Database
CREATE DATABASE databasename;
pg_restore -U postgres -d dvdrental C:\users\sample_database\dvdrental.tar
\d ---> describe(used to describe tables, views, sequences, etc. )
\dt ---> describe(lists all tables in the current database)


5. PostgreSQL – Create Database


CREATE DATABASE my_test_db2
 WITH ENCODING='UTF8'
 OWNER=GeeksForGeeks
 CONNECTION LIMIT=30;

**db_name:** It is the name of the new database that we want to create. It must always be a unique name.
**role_name:** It is the role name of the user who will own the new database.
**template:** It is the name of the database template from which the new database gets created.
**encoding:** It specifies the character set encoding for the new database. By default, it is the encoding of the template database.
**collate:** It specifies a collation for the new database.
**ctype:** It specifies the character classification for the new database like digit, lower and upper.
**tablespace_name:** It specifies the tablespace name for the new database.
**max_concurrent_connection:** It specifies the maximum concurrent connections to the new database.


