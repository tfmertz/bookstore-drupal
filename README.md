# Bookstore Drupal Project for Epicodus Assignment

### Tom Mertz

###### May 15, 2015

#### Description

A drupal project that uses basic pages, custom content types, features, contrib modules, and user permissions.

#### Set up

1. `git clone https://github.com/tfmertz/bookstore-drupal.git`
2. `cd` into the root of the project directory
3. Start a localhost server
  * using MAMP:
    1. Open MAMP
    2. Navigate to Preferences -> Web Server
    3. Change the root directory to be the Drupal project root folder
    4. Click _Ok_ and start the server
  * using PHP: `php -S localhost:8000`
4. Import the database
  * Navigate to phpMyAdmin
    * `localhost:8888/phpMyAdmin` for MAMP
    * `localhost/phpMyAdmin` if you have it installed locally and configured with Apache2.
  * Log in if needed
  * Click _Import_
  * Click _Choose File_
  * Browse to the drupal project directory
  * In the `sites/db-backups` directory include the database.sql.gz file
  * Select utf-8 for character set
  * Click _Go_
5. Navigate to `localhost:8000` for PHP or `localhost:8888` for MAMP


#### Technologies Used

* Drupal 7.36
* phpMyAdmin 4.0.10deb1
