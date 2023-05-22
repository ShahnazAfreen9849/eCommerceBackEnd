# eCommerceBackEnd

Description

The E-Commerce Backend is a backend application that manages an e-commerce site's database using Express.js API and Sequelize to interact with a MySQL database. It allows for database models and associations to be quickly created and modified.

Table of Contents

Description
Installation
Usage
License
Contributing
Tests
Questions
Installation

To install necessary dependencies, run the following command:

npm install
Then, to seed the database, run:

npm run seed
You will need to have Node.js and MySQL installed on your computer to use this application. Additionally, remember to configure the .env file to include your MySQL user name and password.

Usage

To start the server, run the following command:

npm start
The application supports the following API endpoints:

GET, POST, PUT, DELETE operations for categories, products, and tags.
Association between products and tags, with a many-to-many relationship.

Walkthrough Video


License

This project is licensed under the MIT license.

Contributing

Contributions are welcome. Please contact the author for further information.

Tests

To run tests, use Postman or a similar API testing tool and run the various GET, POST, PUT, and DELETE requests.

Questions

If you have any questions about the repo, open an issue or contact me directly.