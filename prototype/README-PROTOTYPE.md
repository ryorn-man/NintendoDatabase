# Nintendo Database – Prototype 

## Overview
In this stage, the Nintendo Database web application exists in an unfinished form, and is connected to an early version of the database for the website. Functionality exists to load data from the database, allow the user to choose which entities to view, and display information about these entities in an article.

## Screenshots – Web Application 
This is an early version of the homepage. It is very barebones. The website is organized with a grid layout. Each page loads a prexisting header and footer from PHP files:

![alt text](/prototype/screenshots/prototype-2.png)

PHP for home page:

![alt text](/prototype/screenshots/prototype-1.png)

This is the Games page, which allows the user to view the video games in the database. The website loads data using DatabaseObject.php, and constructs objects from this data, which are used to deliver the data to the pages for viewing. The Overview stage, corresponding to a $stage value of 0, displays all games in the database. The user can also view and browse between individual video games:

![alt text](/prototype/screenshots/prototype-4.png)

![alt text](/prototype/screenshots/prototype-5.png)

![alt text](/prototype/screenshots/prototype-6.png)


The $stage variable loads from a POST request, and determines whether the page should display the overview page (corresponding to a $stage value of 0), or an entry for a specific object. If > 0, $stage tracks the currently-selected entry in the database, allowing the user to view and browse between entries for individual VideoGame objects:

![alt text](/prototype/screenshots/prototype-7.png)

![alt text](/prototype/screenshots/prototype-8.png)

![alt text](/prototype/screenshots/prototype-9.png)

The DatabaseObject connects to the MySQL database, creates objects from the data (in this case, VideoGame objects), and returns them with a public function:

![alt text](/prototype/screenshots/prototype-10a.png)

![alt text](/prototype/screenshots/prototype-11.png)

This is a VideoGame object, which stores data from the database in private variables, and returns them with public functions:

![alt text](/prototype/screenshots/prototype-12.png)

![alt text](/prototype/screenshots/prototype-13.png)

## Screenshots – MySQL Database
This is an early version of the MySQL database providing data for users to view in the web application:

![alt text](/prototype/screenshots/prototype-3.png)
