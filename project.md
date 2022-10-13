# CLIENT SERVER ASSIGNMENT


#### IMPLEMENT A CLIENT SERVER ARCHITECTURE USING MYSQL DATABASE MANAGEMENT SYSTEM (DBMS).
### STEP 1 
Create and configure two Linux-based virtual servers (EC2 instances in AWS).
![](/Capture2.PNG)
### STEP 2
On mysql server Linux Server install MySQL Server software

`
sudo yum install mysql-server
`


### STEP 3 
On mysql client linux server install mySQL client Software 

`
sudo yum install mysql-server
`
### STEP 4
configure mySQL server to allow connections from remote hosts. 

`
sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf
`

Replace '127.0.0.1' to `0.0.0.0'
![](/config%20file.PNG)

6.From mysql client Linux Server connect remotely to `mysql server` Database Engine without using `SSH`. You must use the mysql utility to perform this action.

![](/Capture3.PNG)

7.Check that you have successfully connected to a remote MySQL server and can perform SQL queries:

![](/Capture4.PNG)