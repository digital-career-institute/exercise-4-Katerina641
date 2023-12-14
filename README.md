# write steps as below and make a document to refer in future
1. write a command to update (sudo apt update)
2. write a command to upgrade
3. write a command to install sql server
4. write a command to  install sql client
5. write a command to check my sql version
6. write a command to start mysql
7. write a command to stop mysql
8. write a command to restart mysql
9. write a command to start sql editor to write queries
10. write a command to create database
11. write a command to create user
12. write a command to grant all permisiion for that user on specific database
13. write a command to show all grants for specific user
14. write a command to create database
15. write a command to create table
16. write a command to insert values in table
17. write a command to display total number of tables
18. write a command to display total number of databases
19. write a command to get all values from particular table
20. write a command to show number of antries
21. write a command to alter the table


    ///////////////////////////////


 
 
 
Updating and Upgrading:  
Update Package Lists: 
sudo apt update 
 
Upgrade Installed Packages: 
sudo apt upgrade 
 
Installing MySQL Server and Client:  
Install MySQL Server: 
sudo apt install mysql-server 
 
Install MySQL Client: 
sudo apt install mysql-client 
 
Checking MySQL Version and Managing Service:  
Check MySQL Version: 
mysql –version 
 
Start MySQL Service: 
sudo service mysql start 
 
Stop MySQL Service: 
sudo service mysql stop 
 
Restart MySQL Service: 
sudo service mysql restart 
SQL Editor and Database Management:  
Start SQL Editor (MySQL CLI): 
mysql -u root -p 
 
Create Database: 
CREATE DATABASE your_database; 
Create User: 
CREATE USER 'your_user'@'localhost' IDENTIFIED BY 
'your_password'; 
 
Grant All Permissions: 
GRANT ALL PRIVILEGES ON your_database.* TO 
'your_user'@'localhost'; 
FLUSH PRIVILEGES; 
 
Show Grants for User: 
SHOW GRANTS FOR 'your_user'@'localhost'; 
Create Database (again, for clarity): 
CREATE DATABASE database_name; 
 
Table Operations:  
Create Table: 
CREATE TABLE your_table ( 
    id INT, 
    name VARCHAR(50), 
    description TEXT, 
     
); 
Insert Values into Table: 
INSERT INTO table_name (id, name) VALUES (1, 'Mahmoud'); 
 
Display Total Number of Tables: 
SHOW TABLES; 
 
Display Total Number of Databases: 
SHOW DATABASES; 
 
Get All Values from Particular Table: 
SELECT * FROM table_name; 
 
Show Number of Entries in a Table: 
SELECT COUNT(*) FROM table_name; 
 
Alter the Table (add a new column, for example): 
ALTER TABLE table_name 
ADD COLUMN new_column VARCHAR(50);

