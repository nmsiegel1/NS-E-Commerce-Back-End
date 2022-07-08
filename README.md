# E-Commerce-Back-End

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## About

This is the back end for an e-commerce applicaiton made with Express.js API and Sequelize to communicate with a MySQL database.

## Table of Contents

* [Made-With](#Made-with)
* [Install](#Install)
* [Notes](#Notes)
* [Video](#Video)
* [Screenshots](#Screenshots)
* [Liscense](#Liscense)
* [Credits](#Credits)
* [Questions](#Questions)

## Made-With 

* Sequelize
* Express.js 
* Node.js
* ES6
* MySQL

Additional
Insomnia

## Install

To install dependencies, run "npm i" or "npm install" in the command line. The user must also create a .env file and add their local MySQL login information to access the database. 

## Notes
* Once dependencies have been installed the user must create a .env file and enter thier login information for MySQL to access the database. 
* Access the databse by logging into MySQL in the command line and run 'SOURCE db/schema.sql;' followed by 'USE ecommerce_db;'
* Once that is complete quit out of MySQL and seed the database by running 'npm run seed' in the command line. 
* When you are ready to access the database run 'npm start' and you will see the message 'Now Listening' in the console. 
* To interact with the database use Insomnia to test CRUD opperations for Category, Product and Tag models. You are able to GET, PUT, POST and DELETE for each model. 
* The routes for each model are: 
    * http://localhost:3001/api/categories 
    * http://localhost:3001/api/products
    * http://localhost:3001/api/tags


## Video

https://watch.screencastify.com/v/2huEHnC8x0rAeyVs9fzV

## Screenshots 

GET category by Id

<img width="1030" alt="Screen Shot 2022-07-08 at 11 12 40 AM" src="https://user-images.githubusercontent.com/102773691/178021023-a9cc9745-cf74-4eb2-9ff0-612ce60d2320.png">

GET all tags

<img width="1029" alt="Screen Shot 2022-07-08 at 11 12 52 AM" src="https://user-images.githubusercontent.com/102773691/178021038-ee2d2094-6af4-4919-92e0-aa832ecd1081.png">

POST product

<img width="1014" alt="Screen Shot 2022-07-08 at 11 13 09 AM" src="https://user-images.githubusercontent.com/102773691/178021046-be95dd17-727c-486d-8115-a6046f68c4fa.png">

PUT product 

<img width="1026" alt="Screen Shot 2022-07-08 at 11 13 19 AM" src="https://user-images.githubusercontent.com/102773691/178021067-de79660a-c95b-4de2-9be7-5db97689a8ab.png">


## Liscense

 This project is liscensed under the MIT liscense.
 
## Credits

Made by Nina Siegel

## Questions

For questions, open a new issue. 

To see more of my work visit https://github.com/nmsiegel1/




