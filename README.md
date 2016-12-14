**Server Assignment 3 | University of Trento**

SOAP Web Services

## Server

* ```introsde.document.dao```: it contains LifeCoachDao.java that manages the connection to the database;
* ```introsde.document.endpoint```: it contains PeoplePublisher.java that exposes the server functionalities;
* ```introsde.document.model```: it contains Person.java and Measure.java that represent the corresponding tables in the database.
                                 They also contain methods to query the database;
* ```introsde.document.ws```: it contains the interface People.java and its implementation PeopleImpl.java 
                              that respectively declare and implements all the server functionalities.

## Configuration files

* ```build.xml```: it contains all the targets to run the code;
* ```ivy.xml```: it contains all the dependencies needed to run the project and it downloads them.

## Setup

The server is deployed on Heroku and it is possible to clone it with:
* https://github.com/AlessioSpallino/introsde-2016-assignment-3-server.git

