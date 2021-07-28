# E-Commerce Backend

* This project was to connect the backend process of an already existing E-Commerce site. 
* The API was already in place. It mostly required routing work to ensure everything was linked appropriately to make the server fully functional for the clients needs. 
* This program utilizes dotenv, express, mySql2, and sequelize.

The following functionality was setup:
    * GET all categories
    * GET one category by ID
    * UPDATE a category
    * CREATE a category
    * DELETE a category
    * GET all products
    * GET one product by ID
    * UPDATE a product
    * CREATE a product
    * DELETE a product
    * GET all tags
    * GET one tag by ID
    * UPDATE a tag
    * CREATE a tag
    * DELETE a tag

To install dependencies:
```
npm i
```
To seed the DB:
```
node seeds /index.js
```
To start:
```
nodemon server.js
```

A walk through demonstration of the program is available [here](https://drive.google.com/file/d/1fNEDBlpOrrBS8LnMFVSbPJ_Au1OTS1_I/view?usp=sharing).

![Screenshot](https://github.com/lyndsielane/ecommerce-back-end/blob/main/Assets/Photo/Screen%20Shot%202021-07-27%20at%208.38.37%20PM.png?raw=true)