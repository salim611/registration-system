# Registration-system 

##Table of contents
- [Registration-system](#registration-system)
  - [Introduction](#introduction)
  - [Objectives](#objectives)
    - [specific objectives](#specific-objectives)
  - [The user of the system](#the-user-of-the-system)
  - [Functional requirements](#functional-requirements)
    - [Home page module](#home-page-module)
    - [registration module](#registration-module)
  - [Software design specification](#software-design-specification)
    - [User interface design](#user-interface-design)
      - [Home page design](#home-page-design)
      - [Registration form](#registration-form)
    - [Database design](#database-design)
      - [student table](#student-table)
      - [next of kin table](#next-of-kin-table)
  
  

## Introduction
This system was decided by the college to ease and smoothen the regisration of new students at comfort of their homes. All new student who have access to the internet and want to join the college will be able to access the colleges website and fill the registration form and qualified students will get admission letter through the email they provided.

Through this system the college will be able to:-
  1. Admit a large number comfortably without people overcrowding at premises
  1. Save the time people use to come to college to register

HTML, PHP and SQL will be the languages used to develop this system. Whe the system is complited registration will be easy to both the students and administration 
      

## Objectives
  Our main objective is allowing every potential student a chance to join college if the meet the neccessary requirements
  ### specific objectives

  1. To create a home page management system to allow navigation arround the site
  1. To create create a contacts management system to give access to new users to communicate to the college
  1. To create a registration management system to help in managing the registration forms
    

## The user of the system
This system will consist of two users:-
- The admin - who will be able to check the information provided by the guest and either accept or deny them admission letters.
- The guest - Who will be possibly the student and will be able to access the registration form.

## Functional requirements

The system will contain just two module since its just a simple system for registration. That is home page and registration module
### Home page module
 It will provide the user with
 1. contacts page
 1. about the college
 1. Vision of the college
 1. a link to registration form
 1. requirements needed to join the college
### registration module
This will basically contain the form to be filled and submitted online for the desired intake

## Software design specification

This is the basic look of the system for the end user and the database. It will contain images and sketches of interfaces desingn in general

In this case there will be user interface and the database interface


### User interface design
This is to show the desired appearance of the system to the end user. It contains sketches of the real interface
#### Home page design
#### Registration form
### Database design

This will give the basic idea of how the database would look like after full complition of the system 
#### student table

|column        |  type       |
|--------------|-------------|
| first name   | tinytext    |
|last name     | tinytext    |
|id no         | int(pk)     |
|phone no      | int         |
|email         | text        |

#### next of kin table

|column        |  type       |
|--------------|-------------|
| first name   | tinytext    |
|last name     | tinytext    |
|id no         | int(pk)     |
|phone no      | int         |
|email         | text        |