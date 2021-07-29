# commands
Some useful command 

Composer for downgrade from 2 or update into 1 version:-
  composer self-update --1
--------------------------------------------------------------

Command to import the Dabase in mysql
  mysql -u root -p DatabaseName < path/to/YourDatabaseFile.sql

Command to export the Dabase in mysql
**To make easy to export the database use the path mysql/bin
**mysql/bin>**
  mysql -u root -p DatabaseName > CreateDatabaseName.sql

-------------------------
Alternative solution to import and create the database.

 1.   create database YourDatabaseName;
 2.   use YourDatabaseName;
 3.   source path/to/YourDatabase.sql;

----------------------
