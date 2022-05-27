# E-Commerce-BackEnd

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Technology](#technology)
- [Links](#links)

## Description

Our task this week is to build the back end for an e-commerce site by modifying the starter code provided for us. We need to configure a working Express.js API to use Sequelize to interact with a MySQL database. We also need to provide a walkthrough video that demonstartes its functionality.

## User Story

    AS A manager at an internet retail company
    I WANT a back end for my e-commerce website that uses the latest technologies
    SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

    GIVEN a functional Express.js API
    WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    THEN I am able to connect to a database using Sequelize
    WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data
    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database
    WHEN I open API GET routes in Insomnia for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia
    THEN I am able to successfully create, update, and delete data in my database

## Installation

1. Clone the git repository.
2. Run npm install to install dependencies.
3. Log in to your MySQL and input
   ```terminal
   source db/schema.sql
   ```
   and to access the schema. Then input
   ```terminal
   use ecommerce_db
   ```
   to select the correct database.
4. Once those steps have been executed, quit out of your MySQL and input
   ```terminal
   npm run seed
   ```
   to seed data to your database.
5. Once that's done, input
   ```terminal
   node server.js
   ```
   to start running the application.

## Screenshots

## Technology

1. Node.js
2. MySQL
3. Express
4. Sequelize
5. Dotenv

## Links

Email: andynguyen_3@hotmail.com <br />
Github: https://github.com/androneus14 <br />
