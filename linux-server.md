# Bash

* Variable default: `CVAR="${1:-foo}"`


# MySQL / MariaDB

Create a new user and database, and allow access to tis user

    CREATE USER '<USERNAME>'@'localhost' IDENTIFIED BY '<PASSWORD>';
    CREATE DATABASE "<DATABASE_NAME>";
    GRANT ALL PRIVILEGES ON <DATABASE_NAME>.* To '<USERNAME'@'localhost' IDENTIFIED BY '<PASSWORD>';
    FLUSH PRIVILEGES;

    
# Image Processing

* ImageMagick: `identify <filename>` to get infos about an image
* `jpegoptim` to optimize jpegs
* `optipng` to optimize pngs
