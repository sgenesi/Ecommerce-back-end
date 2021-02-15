# E-Commerce Back End

## Description

This is the backend portion of an E-Commerce website that uses an SQL database that includes tables for categories, products, tags, and product tags.  Express.js was used for the server along with Sequelize as the ORM to run SQL models and queries. 

## Table of Contents
* [User Story and Acceptance Criteria](#user-story-and-acceptance-criteria)
* [Built With](#built-with)
* [Installation](#installation)
* [Links](#links)

---
## User Story and Acceptance Criteria


### User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
```
```
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
```
```
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
```
```
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
```
```
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

---
## Built With
* Node
* Express
* MySQL
* Sequelize
* Dotenv

---
## Installation
* Both Node.js and MySQL must be installed on your computer
* Clone the repo https://github.com/sgenesi/ecommerce-back-end
* Navigate to your root directory and run <code>npm install</code>
* To start server, run <code>npm start</code> in your command line

---
## Links
* Walkthrough Video: https://screencast-o-matic.com/watch/crnohVSyYS
* GitHub Repo: https://github.com/sgenesi/ecommerce-back-end

---




