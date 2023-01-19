# InStock
Instock is an Agile project to deliver a full stack Inventory Management System with a modern React and SCSS front-end communicating with back-end, that was build with Node.js (Express.js). Knex.js was used as an SQL query builder in Node.js., it was used for model schema creation, table migrations, connection pooling and seeding.

The website is fully responsive for mobile, tablet, and desktop viewing and users can add, edit or delete both warehouses and inventory items (full CRUD operations). 

## The Team

This project was built with the collaboration of: <br>
[Nanaya Miki](https://github.com/Lala0419) <br>
[Hester L](https://github.com/hlai52) <br>
[Emily Wong](https://github.com/emwong101) <br>


## Tech Stack and Tools
* HTML, SASS, JavaScript, React, React Router, Node, Express, API's , MySQL, Knex.js, Axios

## Installation:
1. To install and run the project you will need to clone or dowload the Front-end file - [instock](https://github.com/NacarateJ/instock), and the Back-end file - [instock-api](https://github.com/NacarateJ/instock-api);
2. Run ```nmp i``` to install all the required packages for the app;
3. To start the Front-end run the command ```npm start```;
4. To start the Back-end run the command ```npm run server```;

## Environment Variables
1. Front-end:
Add the following variables in .env file:

```REACT_APP_API_URL=https://localhost:8080```
  
2. Back-end:

```DB_LOCAL_DBNAME="instock_api"```<br>
```DB_LOCAL_USER="YOUR DB USER NAME"```<br>
```DB_LOCAL_PASSWORD="YOUR DB PASSWORD"```<br>
```PORT = 8080```



## Knex

Knex is a SQL query builder, mainly used for Node.js applications with built in model schema creation, table migrations, connection pooling and seeding.

### Install Knex and Knex Command Line Tool

Install `knex` __globally__ on your local computer.

```bash
$ npm install knex -g
```

This will allow us to use `knex` as a command line tool that helps you create and manage your knex files.

In addition, you will need to also install the `knex` module __locally__ to use in your project.

```bash
$ npm install knex --save
```

## Configuring your database

We're going to be connecting to a MySQL database, we'll need to install the `mysql` module.

```
$ npm install mysql --save
```

We can start by creating a `knexfile.js` in the root of your project which will act as our configuration for different environments, (e.g. – local development vs production).

```
$ knex init
```

This will create a `knexfile.js` with the different configurations for the different environments.


