# Object-Relational Mapping (ORM) E-commerce Back End Database

A application working Express.js API and configure it to use Sequelize to interact with a MySQL database.

# Installation

How to install :
- (ORM) is deployed by using node server.js
- If choosing to use from terminal, open terminal and run
- npm install mysql2
- npm install sequelize
- npm install dotenv
- node server.js , npm run seed

## Create the schema, seed the database and start the application’s server.
 ![Demo](gifs/CREATE DATA.gif)

## GET routes for Categories, Products, and tags, and single category, a single product, and a single tag
 ![Demo](link) 

## POST, PUT and DELETE routes for categories, products, and tag
 ![Demo](link) 

# Object-Relational Mapping (ORM) Information
- Contains four models : Category, Product, Tag, ProductTag
- Product belongs to Category, as a category can have multiple products but a product can only belong to one category.
- Category has many Product models.
- Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.
- Tag belongs to many Product models.

## Usage
[Watch the video]()

## Questions
Contact email: NEEKO_TVXQ@HOTMAIL.COM

GitHub: [NEEKO623](https://github.com/NEEKO623)

Please contact my email.