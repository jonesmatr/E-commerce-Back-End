
## E-commerce Back End

### Description

This application provides a back end for an e-commerce site. Using Express.js API and Sequelize, it interacts with a MySQL database to manage an online store's products, categories, and tags.

The walkthrough video can be accessed [here](https://drive.google.com/file/d/1Vk57fEjk9O3qHy7sBk-wVttxou1AzcT7/view?usp=sharing).

### Features

- CRUD operations for products, categories, and tags.
- Associations between products and categories, and products and tags using Sequelize models.
- Error handling and data validation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies)

### Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the required dependencies.
4. Set up your MySQL database and update the `config/connection.js` with your database credentials.
5. Run `npm run seed` to seed the database with sample data (if needed).
6. Start the server by running `npm start`.

### Usage

Use tools like Postman or Insomnia Core to test API routes for creating, updating, deleting, and retrieving data.

### Technologies Used

- Node.js
- Express.js
- MySQL
- Sequelize ORM

