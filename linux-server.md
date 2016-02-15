# MySQL / MariaDB

Create a new user and database, and allow access to tis user

    CREATE USER '<USERNAME>'@'localhost' IDENTIFIED BY '<PASSWORD>';
    CREATE DATABASE "<DATABASE_NAME>";
    GRANT ALL PRIVILEGES ON <DATABASE_NAME>.* To '<USERNAME'@'localhost' IDENTIFIED BY '<PASSWORD>';
