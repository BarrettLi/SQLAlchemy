Introduction:
Use SQLAlchemy to connect MySQL database and create tables that are needed for a blog.

Project Objectives:
- Use SQLAlchemy to connect databases
- Understand the relationships between different tables
- CRUD operations through SQLAlchemy
- Learn to use Faker

Preparation:
1. Install MySQL, SQLAlchemy and Faker
   In Linux,
   $ sudo pip install mysql
   $ sudo pip install sqlalchemy
   $ sudo pip install faker
   $ sudo apt-get install python-mysqldb
2. Configuration
   Open MySQL configuration file:
   $ sudo vim /etc/mysql/my.cnf
   and then add the following settings:
   [client]
   default-character-set = utf8
   [musqld]
   character-set-server = utf8
   [mysql]
   default-character-set = utf8
3. Start MySQL and create a database
   $ mysql -uroot -p
   >create database blog;