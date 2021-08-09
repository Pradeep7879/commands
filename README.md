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
  mysqldump -u root -p DatabaseName > CreateDatabaseName.sql

-------------------------
Alternative solution to import and create the database.

 1.   mysql -u root -p
 2.   create database YourDatabaseName;
 3.   use YourDatabaseName;
 4.   source path/to/YourDatabase.sql;

----------------------
Alternative solution to import and Export the database in **lando**.

lando db-import file_name.sql
lando db-export file_name.sql

==================================================================================================================================================================

Useful command for UBUNTU OS

1.  sudo means superUser, some command have run with sudo.
2.  sudo servies apache2 stop/start
3.  sudo servies mysql stop/start
4.  sudo /opt/lampp/lampp stop/start
5.  sudo /etc/init.d/apache2 start/stop
6.  sudo /etc/init.d/mysql start/stop
7.  sudo apachectl start/stop
8.  sudo systemctl start/stop apache2.service

=================================================================================================================================================================

Using XAMPP in LAMPP for UBUNTU

