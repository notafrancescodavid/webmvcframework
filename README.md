# webmvcframework - PHP Web MVC Framework
The webmvcframework package is an object oriented PHP framework that uses MVC architectural design pattern for building web applications with MySQL database and HTML 5.

It offers to developers a complete set of functionalities for rapid development of data intensive web applications. Specifically, it provides services for system decomposition to simplify the design and development of complex web applications. It is based on the MVC design pattern and on the concept of application's decomposition, this leads to two main goals:
* Simplifies the collaboration process among people having different knowledge (e.g. GUI designers, system designers, developers and so on)
* It guides for a more maintanable and reusable code

The framework provides the interfaces to reduce the amount of code you have to write. So that you can focus on your web app design and not on the recurrent aspects of web application development. These aspects generally are related to the database (e.g. data listing, data listing and sorting, data listing and filtering, data listing and pagination, record management and common table’s operations for select, insert, delete and update records) and server side logic. 
The components are Controllers that can be aggregated to create and manage complex behaviours, in a Object Oriented fashion, and that ensure the semplification of the development process in particular in big projects and in projects managed by groups of developers. The components are generally useful to manage data sets and show it in the GUI, but can also be used only for server side logic programming.

[Documentation link](https://github.com/rcarvello/webmvcframework/tree/master/docs)

## Prerequisites
* Apache web server
* PHP 5.* 

## How to install
To install download and copy it into an Apache web folder. Then go to the config directory and modify application.config.php according to your MySQL server configuration and Apache web folder you used to deploy your application.
By default framework is provided with simple examples. You can decide to remove them by clearing the models, controllers, templates and views directories.
I will provide further examples in the future to illustrate all its functionalities.

## How to autogenerate PHP Model classes from your MySQL database
The util directory contains a file named **app_create_beans.php**.
Run it from your browser or from command line for executing ORM autogeneration engine

Before running it you must configure MySQL access parameters by modifying **util\mysqlreflection\mysqlreflection.config.php** according to your MySQL configuration.
After running the generation utility the autogenerated PHP classes will be placed into the **models\beans directory**.

## UML Diagrams of framework classes
### Overview
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/framework.png)
### Request processing and dispatching
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/Dispatch%20and%20Create%20MVC%20Instance.png)

#### See the docs folders for more information
[Documentation link](https://github.com/rcarvello/webmvcframework/tree/master/docs)

### Introduction to PHP WEB MVC Framework - Video Tutorial
[![IMAGE Video Tutorial](https://i.ytimg.com/vi/7zJFXLd4rk8/hqdefault.jpg?custom=true&w=196&h=220&stc=true&jpg444=true&jpgq=90&sp=67&sigh=5Dym90YTR05kyX82Kg8gW9VseUk)](https://www.youtube.com/watch?v=7zJFXLd4rk8&t=37s)
