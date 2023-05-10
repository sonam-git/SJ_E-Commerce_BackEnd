# SJ_E-Commerce Back End.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
## Description
The back-end database has been purposed towards e-commerce websites using Express.js API and Sequelize to connect to the MySQL database. The back-end database allows users to create a development database, seed it with test data, and sync Sequelize models to MySQL database. User's have the ability to use GET, POST, PUT, and DELETE routes to display and manipulate data in the users database. 
## Table of Contents:
- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [Usage Information](#usage-instructions)
- [Solution URL](#solution-url)
- [Demo Walkthrough Video](#demo-walkthrough-video)
- [Screenshots](#screenshots)
- [Installation Process](#Installation-Process)
- [Built With](#Built-With)
- [What I Learned](#What-I-Learned)
- [Continued Development](#Continued-Development)
- [License](#License)
- [Author](#Author)

# Overview

## The Challenge:
This challenge requires the creation of an e-commerce back-end site that meets specific user requirements. These requirements include the ability to connect to a MySQL database using Sequelize, create a development database that is seeded with test data, sync Sequelize models to the MySQL database, and display data from categories, products, and tags in a formatted JSON. The application should also be able to create, update, and delete data in the database using any API testing, where i've used Postman.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## Usage Instructions
1. Repository: Open documentation run 'npm i' and update '.env'.
2. Create database: use the schema.sql file in the db folder with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
3. Run 'npm run seed' to seed the database with test data. Then, run 'npm start' or 'nodemon' to start the server and sync the Sequelize models to the MySQL database.
4. Generate a development database with test data, use the schema and seed commands.
5. Use Postman to test http://localhost:3001 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database.


## Solution URL:
[GitHub Repository:](https://github.com/sonam-git/SJ_E-Commerce_BackEnd)

## Demo Walkthrough Video:

### GET routes to return all categories, all products, and all tags being tested in Postman:
[ => Click to Watch](https://drive.google.com/file/d/1MpSizOa71GpimyIjenDZwLYDhUlYxkRJ/view)

### GET routes to return a single category, a single product, and a single tag being tested in Postman:
[ => Click to Watch](https://drive.google.com/file/d/1YWHdhlhfwjORegcjbm-KKHQumup5NuOt/view)

### POST, PUT, and DELETE routes for tags, categories, and products being tested in Postman:
[ => Click to Watch](https://drive.google.com/file/d/1SMcwih_EWh4a3_zyMFZuuFbc5QQT7W75/view)


## Screenshots:

![Screenshot 2023-05-08 at 2 29 38 PM](https://user-images.githubusercontent.com/89502092/236944575-0dadbb80-013c-4f78-9190-208d1914fa2c.png)


## Installation Process
1. Clone the Repository from GitHub (or) Download Zip Folder from Repository from GitHub.
2. Open the cloned (or downloaded) repository in any source code editor.
3. Open the integrated terminal of the document and complete the respective installation guides provided in "Built With" to ensure the cloned documentation will operate.

## Built With
- JSON:[ JSON](https://www.npmjs.com/package/json)
- Dynamic JavaScript
- Dotenv: [8.6.0](https://www.npmjs.com/package/dotenv)
- Express: [4.17.1](https://www.npmjs.com/package/express)
- Node.js: [Version 16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- Express.js:[Express.js](https://expressjs.com/en/starter/installing.html)
- Node MySql2: [2.3.3](https://www.npmjs.com/package/mysql2)
- Sequelize: [6.29.3](https://www.npmjs.com/package/sequelize)
- Postman: [Postman](https://www.postman.com/)
- Nodemon: [2.0.12](https://www.npmjs.com/package/nodemon/v/2.0.12)
- License Badge: [Shields.io](https://shields.io/)
- Visual Studio Code: [Website](https://code.visualstudio.com/)

## What I Learned:
1. How to use Express.js to create a functional back end for an e-commerce website.
2. How to connect to a MySQL database using Sequelize and update environment variable files accordingly.
3. How to generate a development database with test data using schema and seed commands.

## Continued Development:
1. Implement the latest technologies, such as Express.js, MySQL, and Sequelize to create a functional back end for the e-commerce website.
2. Ensure that the environment variable file is updated with the database name, MySQL username, and MySQL password to connect to the database using Sequelize.
3. Create schema and seed commands to generate a development database with test data, allowing for a smooth testing process.

## License
This project is covered under the [MIT](https://opensource.org/licenses/MIT) license.

## Author
Follow me on Github at [Sonam J Sherpa](https://github.com/sonam-git).
Additional questions or concerns? feel free to contact me at sherpa.sjs@gmail.com

