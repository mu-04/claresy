## Classroom Reservation System for the PSHS



### Specifications

This codebase was used to solve a problem regarding security (SQL Injections)
It was tested by vulnerability scanners and currently there are no vulnerabilities.

Database Manager: MySQL
Backend Language: PHP
Operating System: Linux
Front-End Framework: Twitter Bootstrap


### Original phpMyReservation Codebase Demo

* [A demo can be found here](http://www.olejon.net/code/phpmyreservation/?demo)
* Create a new user to test it. **Make sure you read the demo information on the new user page!**

### Download

* [Download phpMyReservation 1.0](http://www.olejon.net/code/phpmyreservation/files/phpmyreservation-1.0.tar.bz2)

### Wiki

* [How to install](https://www.olejon.net/code/phpmyreservation/?how_to_install)
* [Reservation reminders](https://www.olejon.net/code/phpmyreservation/?reservation_reminders)

### Features

* Fast, easy and smooth
* User login
* Browse through all weeks of the year
* A price per reservation can be set
* Usage is stored automatically
* User control panel
* Advanced admin control panel
* Receive reservation reminders by email

**NOTE:** This web app was intended to be run on a server that is in the same time zone as the users, so there is no time zone support, as it was intented to be a private project. If all users are in the same time zone and the server is in another, use [this PHP function](http://php.net/manual/en/function.date-default-timezone-set.php) at the top part of `main.php` to change it. It all users are not in the same time zone it is not supported and the code must be changed more.

### Requirements

**Server:**

* Web server with PHP
* MySQL

**Client:**

* A modern browser
