# eComBackEnd

## Installation
To make sure everything is running smoothly I had to install the seed, nodemon, dotenv, express, mysql2, and sequelize.
The seeds were already installed and so was the connection.js

## Models

With the models; I just had to define the columns so with the Category.js, Product.js, ProductTag.js, and Tag.js. 
With the index.js the products had to belong to Category, and if not then on delete it will delete everything associated with that category. Them, the catories have many products, so I had to write a code using the foreigh key as category_id. Since the Products belong to may tags, I had to like the products to the tag through the product tag. Lastly, the tags belognm to many products so I had to link them together using the foreign key tag_id.

## Routes

API
For the category-routes - I had to make sure I find all the categories, and then find one category. I must be able to create a new category, update, and delete the new category. 
It was very similar for the product-routes and tag-routes.

## server.js

For the server.js I just needed to import the sequelize connection, and then sync sequelize models to the database. 

## db

After everything was connected, I then dropped the database and then created the databade again just in case. Finally I ran the codes in the terminal and started using insomia to debug any broken codes.


## Deployed Link
https://adrianabroadnax.github.io/eComBackEnd/

## GitHub Link
https://github.com/AdrianaBroadnax/eComBackEnd.git

## Walkthrough Video
https://watch.screencastify.com/v/lcOOq6tlTmNodakciHh3
