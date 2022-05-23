# E-Commerce Back-End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This back-end command-line application utilizes JavaScript, MySQL, Node.js, and Node Package Manager (Express, MySQL2, Sequelize, Nodemon, Dotenv) to implement Object-Relational Mapping and CRUD functionality to an e-commerce MySQL database.

## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [Preview](#preview)
  - [License](#license)
  - [Contribution](#contribution)
  - [Questions](#questions)
  - [Credits](#credits)

## Installation
- Prior to starting up the program, make sure you have [Node.js](https://nodejs.org/en/download/), [MySQL](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide), and [Insomnia](https://insomnia.rest/download) installed onto your local computer for optimal user experience.

- To install this application, clone this repository onto your local computer, open it in your code editor, and run the following command on your terminal: ```npm install```

- Once all dependencies have been installed, create an environment variable file (.env) at the root level of this application with the following content for successful connection to the database:
    - DB_NAME = ecommerce_db
    - DB_USER = <'mysql-username-here'> (If no username is set, default user for SQL is 'root')
    - DB_PW = <'mysql-password-here'> (If no password is set, by default SQL has no password)

## Usage
- Once all packages have been installed, run the mysql shell command ```mysql -u root -p``` and enter your password (if one has been set) before running ```source db/schema.sql```. Once completed, type ```exit```.

- After exiting the mysql shell, run the command ```npm run seed``` to populate data into your tables. Once the command finishes executing, type ```npm start```, ```npm run start``` OR ```node server.js``` on your terminal to turn on your server.

- Once the server has been turned on, head over to Insomnia to test API GET, POST, PUT, and DELETE routes in order to create, read, update, and delete data in the database.  

## Preview

- GET, POST, PUT, and DELETE Categories



- GET, POST, PUT, and DELETE Products



- GET, POST, PUT, and DELETE Tags



## License
- This project is licensed under: [MIT](https://opensource.org/licenses/MIT)

## Contribution 
- Forking this repository is always welcomed and encouraged!

> If you encounter a problem with this application, please add an issue or pull request to the GitHub repository. 

## Questions
- Please feel free to use this application at any time and visit my personal [GitHub](https://github.com/denysha-abigail) profile to access other open source projects! 

## Credits
- *[Denysha Guerrios-Armaiz](https://github.com/denysha-abigail), 05/2022*
- *[Starter Code](https://github.com/coding-boot-camp/fantastic-umbrella)*