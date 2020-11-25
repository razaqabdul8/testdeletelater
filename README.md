# Passive Income Application
![GitHub license](https://img.shields.io/badge/Made%20by-%40Eng.JordanNaei-orange)
![License](https://img.shields.io/badge/License-ISC-blue.svg "License Badge")

# Description


# Application Functionalities illustration video
![]()

## Technologies and Frameworks Used
- Node.js.
- Express.
- Handlebars.
- My SQL.

# Installation
- Run npm i.
- Run node server.js.

# Database Design
The database design for the passiveincome app involved the creating of a database titled passive_income_db. The passive income database utilized the auto increment MySQL attribute for the creating of a table to store the “ID” parameters by which the various iPhones would be identified and retrieved. This attribute was used because mySQL was needed to assign a sequence of numbers automatically to the given field. This initial column was also defined as “NOT NULL” to enforce a value to always be present in the given field so that a new record could not be added to the field without a value being attributed to it first through this field. 
With the aforementioned terms having been defined, the structure of the database can consequently be discussed. Overall, the database design was carried out in the following steps which provide a general overview of each step taken:
1)	The usage of the “CREATE DATABASE” statement to create a database with the name of “passive_income_db.
2)	The usage of the “USE passive_income_db;” statement to tell MySQL to use the passive_income_db as the current database for subsequent statements. 
-	In other words, the “USE” statement is used to select a database and perform SQL operations into that database. 

<hr>

<p align="center">
  <img src="https://github.com/razaqabdul8/testdeletelater/blob/main/database%20pic.JPG?raw=true"/>
  <br>
  <em>SQL Schema showing the logical collection of database objects described</em>
</p>

3)	The above series of statements are for the creation of a table called “iPhones” thatcontains five columns: id, model, asin_n, upc_n and capacity. 
a.	The id column is of type int, auto increment, and not null and will hold an integer. 
b.	The model column is of type varchar, not null and will hold characters and the maximum length for this field is 256 characters. 

# Test


# Repository

- [Project Repo](https://github.com/JordanNaei/passiveIncome)

