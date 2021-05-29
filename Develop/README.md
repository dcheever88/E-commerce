## E-Commerce Backend

This is an e-commerce backend code.

# User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Installation

In terminal:

* npm init
* npm install mysql2 sequelize dotenv

In the root directory for your project:
* mysql -u root -p

Enter your password
In mysql:
* source db/schema.sql
* quit;

In terminal:
* npm run seed
* npm start

## Usage

* To test routes, please watch the linked instructional video!
* https://drive.google.com/file/d/1M-4D0gyJXvLCPO-fGZ9nT5lY8mvf35Hc/view

## Built Using

* MySQL2, Express, Sequelize, dotenv, ES6
