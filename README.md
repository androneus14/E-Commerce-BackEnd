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

server.js file with added sequelize code to sync sequelize to the database
![vscode-server js](https://user-images.githubusercontent.com/98381243/170668694-22ed98c4-4213-48e1-9466-2d313c2a1b27.png)

Category routes with GET, POST, PUT, DEL to run through Insomnia
![vscode-cat-routes](https://user-images.githubusercontent.com/98381243/170668789-e8bd60c3-fa4b-46b9-8d6c-e2af39c734d0.png)

Tag routes with GET, POST, PUT, DEL to run through Insomnia
![vscode-tag-routes](https://user-images.githubusercontent.com/98381243/170668835-6ece650b-377d-4f44-92e4-11f90b7c5e2a.png)

Getting all categories
![insom-getAll](https://user-images.githubusercontent.com/98381243/170668866-b2d7476d-5262-47dd-8b76-2ce2a16e9a49.png)

Creating a new category
![insom-createCat](https://user-images.githubusercontent.com/98381243/170668900-d90d795b-7f16-4471-8d97-5e21c4c945d0.png)

Updating a category
![insom-updateCat](https://user-images.githubusercontent.com/98381243/170668978-e5e4de90-a724-4b8a-a279-2e30985d9487.png)

Deleting a category
![insom-deleteCat](https://user-images.githubusercontent.com/98381243/170668996-9acce735-4508-4e52-9007-2bebee13c106.png)

## Technology

1. Node.js
2. MySQL
3. Express
4. Sequelize
5. Dotenv

## Links

Email: andynguyen_3@hotmail.com <br />
Github: https://github.com/androneus14 <br />
Demo Videos:
1: https://drive.google.com/file/d/1qy3zc-U1laVdRv--mFGU4fw3r7Qcuj1H/view <br />
2: https://drive.google.com/file/d/14RfdhlVkzGQyBGctGRoTLq_chcosp9nG/view <br />
