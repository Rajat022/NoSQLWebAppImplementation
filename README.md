# NoSQLWebAppImplementation

Introduction
Goal: The aim is to create a web page that allows the display and ranking of movies 
from a database, as well as providing functionality to add, edit, and delete a movie.

Overview
Model for this web page includes a main frame displaying a dropdown list of films 
sorted in ascending alphabetical order of the title, read-only information about the 
selected movie, buttons for rating and deleting the displayed movie, and a button to 
add a new film. The architecture for this project follows the MVC pattern, with the 
model being the class Film View, a JSP to display the frames, the controller to 
interpret requests, and a class to connect to the NoSQL database. In this report, we 
will explore the implementation of this web application using MongoDB and 
provide details on how to test and configure the database.

II. Requirements and Specifications
This project utilizes the full Stack, a comprehensive full stack web development 
methodology. The combines four essential tools: MongoDB, Express’s, AngularJS, 
and NodeJS. To design the website, we will be following the conventional MVC 
Architecture, which consists of Model, View, and Controller. 
The Model handles the database connection string and database creation, while the 
View refers to the User Interface, which showcases the website's output. The Controller 
is responsible for managing all the control data push and fetching processes between the 
Model and View. Finally, we create the server.js file, which acts as a Rest-API for 
connecting the User Interface to facilitate data transition.
