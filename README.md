# Netflix Clone
Used JavaScript, PHP,HTML,CSS and MySQL to create a web based Netflix clone which allows users to stream movies, series, documentaries etc.

- Working Version of Full Stack Netflix Clone build using HTML5, CSS, jQuery/Ajax and PHP.

  ![register](https://github.com/bhanupratap78/Netflix_clone/blob/master/assets/demo/demo.gif)

## Table of Content
- [Installation](#Installatio)
- [Frontend And Backend Languages Used](#Frontend-And-Backend-Languages-Used)
- [Motivation](#Motivation)

## Installation
- Download XAMPP for the respective version of OS from https://www.apachefriends.org/index.html.

- Once XAMPP is installed and lauched:

  - Under the General tab, click Start.

  - Under the Service tab, click Start on both Apache and MySQL services.

  - Under the Network tab, click Enable.

    (This would start the local server at port 8080 on your machine)

  - Under the volume tab, click Mount

  - On the XAMPP virtual machine, click on lampp folder and then htdocs folder. Place the Netflix_clone folder into the htdocs folder.

- Go to http://localhost:8080/phpmyadmin to go into the admin page and click the "New" button on the left  side of the screen to create new database. On the right side of the screen under the input for Create database, type in Netflix and then click the "Create" button.

- Click on the newly created database "Netflix" on the left side of the screen and go to "Import" on the right side of the screen, locate the file in the git repository in sql folder called database-STRUCTURE-AND-DATA.sql and then click "Go" to import all the SQL instructions for creating the tables and entries for each table in the database.

- Now go to http://localhost:8080/Spotify_Clone/register.php to access the registration page, Make sure to register for your own user profile and then log in to the system.

- Now in order to stream videos user must subscribe the services, for that you can paypal account details like ClientID, ClientSecret in paypalConfig.php file, then you can click on Subscribe to Netflix in user tab, or you can edit your users isSubscribed value to 1 in users table in database.

## Frontend And Backend Languages Used
- HTML
- CSS
- JavaScript
- JQuery
- PHP

## Motivation
This project was created by me mainly to teach myself JavaScript, PHP,HTML,CSS and MySQL. Since the point of this project was not to make great UI/UX design choices, I chose to create a clone of a well established product as to shorten my learning time and not to focus on the wrong thing. Since I am already a heavy Netflix user and therefore I thought it would be an interesting challenge to tackle.
