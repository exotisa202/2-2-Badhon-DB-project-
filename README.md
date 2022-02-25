# 2-2-Badhon-DB-project-

This a Online Blood Donation Management System comprised of a Client app and an Admin app.
This was the term project of BUET Level 2 Term 2 of Database Course (CSE 216).

Authors

@exotisa202
Technology Used
NodeJs and ExpressJS (For Backend)
HTML, CSS, javascript (Client and Admin App Frontend)
Oracle 19c (Database)
Installation
Oracle Installation
The database used in this app is Oracle 19c Database. If you don't have Oracle installed in your system, you need to install it first to run the app in your system. To install Oracle, you can follow the given link below:

Oracle Installation Guideline for Windows 10

After completing the installation, you will need to setup the database schema. You can create your own schema and provide the credentials into the serverInformation.js file located in the /server directory.

Run the snippets below in SQL Plus while being connected as sysdba.
Set Up Database:
Create User/Database
Log in to SQL Plus with sysdba

create user c##BADHON identified by password;
grant dba to c##BADHON;
Sign into your schema by providing these credentials:

  connect c##BADHON;
  password: 123456
In this way, your schema will be ready to hold the database tables. The SQL Dump file is provided in the root directory. Import them into your newly created schema.

For database creation and table configuration, we have used Navicat Premium 16.


Node Installation
Install Node on your device
Clone the repository
Install all the dependencies from package.json

cd to server directory
  npm i
  npm install
Start the node app

 npm start
Goto

 http://localhost:5000
cd to client directory
  npm i
  npm install
Start the client app

 npm start
The client app will automatically launch at http://localhost:3000/ If not starting, goto

 http://localhost:3000
