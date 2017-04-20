# MediaManager
Media manager with CRUD operations in database

The program is configured to work on MySQL 5.7, 
there is used mysql-connector-java-6.0.5

Creating the required tables: resources.createTabs.sql

Main-Class: com.manager.AppRunner

executable jar: resources.manager-jar-with-dependencies.jar (file is generated by Maven on phase package)

Run:

1. create tables in database, execute createTabs.sql

2. run executable jar  manager-jar-with-dependencies.jar
