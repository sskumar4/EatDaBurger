## Project Name: Eat-The-Burger
## Title: Eat-The-Burger

![video](Assets/employeetracker.gif)

## Table of Contents

<!-- vscode-markdown-toc -->
* 1. [Link repository](#Linktorepository)
* 2. [Introduction](#Introduction)
* 3. [Technologies](#Technologies)
* 4. [Files](#Files)
* 5. [Features](#Features)
* 6. [Installation](Installation)
* 7. [Launch](#Launch)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Linktorepository'></a>Link to repository

* [Repository](https://github.com/sskumar4/EatDaBurger)
* [Link to Heroku deployment](https://limitless-tor-53439.herokuapp.com/)
  

##  2. <a name='Introduction'></a>Introduction   
Create a  a full stack project burger logger with MySQL, Node, Express, Handlebars and ORM following the MVC design pattern. The app uses Node and MySQL to query and route data in your app, and Handlebars to generate your HTML.

'Eat the Burger' is a full stack app that the front-end and back-end interact with each other. The Front End loads information from the back-end using javascript and Node.js; loading items from the Mysql database, which are then populated by the user based on their burger entries. The app then moves the burgers when the 'Devour it' button is clicked which then is moved it to the devoured burger column.

Users can create custom named burgers and submit through the form.  They are added to the MySQL database.  All database queries are run through a custom built ORM.

##  3. <a name='Technologies'></a>Technologies 
JavaScript, ORM, jQuery, Node.js, Express.js, Handlebars.js, mySQL Database, HTML, CSS, BootStrap, Heroku Jaws_DB

NPM packages -- Express, body-parser, method-override, express-handlebars, mysql

##  4. <a name='Files'></a>Files
Created the following 
SQL files: 
  * eTrackerDB.sql
js files:
  * eTracker.js, eTracker.js

##  5. <a name='Features'></a>Features

### App Setup
 Create a GitHub repo and clone it to your computer.
 Make a package.json file by running npm init from the command line.
 Install the Express npm package: npm install express.
 Create a server.js file.
 Install the Handlebars npm package: npm install express-handlebars.
 Install the body-parser npm package: npm install body-parser.
 Install MySQL npm package: npm install mysql.
 Require the following npm packages inside of the server.js file: 
 express
 body-parser

In this application we make use of html templates with help from handlebars via the express-handlebars node package. We also make use of the MVC paradigm of project management to structure both out file setup, and the content of our script files. We have a homebrewed ORM that is non-database specific, a model script file that ties the ORM to our specific database usage, and then a controller script file to manage our routes. The last little bit of script to handle the router action comes from yet another script file located under our public assets directory, burgers.js. For a project with such small scope the MVC structure may seem like overkill, but that serves as an added purpose for this assignment, by giving us a chance to practice its implementation.

## 6. <a name='Launch'></a>Launch

* Deployed Heroku link to the app: https://limitless-tor-53439.herokuapp.com/
