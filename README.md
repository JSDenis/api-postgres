# api-postgres

#Create db

createdb exampledb1


#Database connection

psql exampledb1


#Get database contents

\dt


#Exiting the database session

\q


#All databases

\l


#Info about db

\c exampledb1


#Create table

\i database.sql


#Create data:

INSERT INTO post (title, content, user_id) VALUES ('Title 1', 'Content 1', 1);



