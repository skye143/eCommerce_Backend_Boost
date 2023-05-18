# eCommerce_Backend_Boost_13

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Table-of-Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Database Configuration](#Database-Configuration)
  * [API Routes](#API-Routes)
  * [Contributing](#Contributing)
  * [Feedback](#feedback)

  ## [Description](#table-of-contents)

This is the backend application for an e-commerce website built using the latest technologies. It provides a functional Express.js API that allows you to manage and interact with the database using Sequelize ORM.

  ## [Installation](#table-of-contents)

Go to my repo and clone the repository:
[https://skye143.github.io/eCommerce_Backend_Boost_13/](https://skye143.github.io/eCommerce_Backend_Boost_13/)

    git clone: git@github.com:skye143/eCommerce_Backend_Boost_13.git

To install the necessary dependencies, run the following command:

    npm install


## [Usage](#table-of-contents)

To start the application, use the following command: 

    npm start

  ## [Database Configuration](#table-of-contents)

Before running the application, make sure to set up your database configuration. Create an environment variable file .env in the root directory and add the following:

    DB_NAME=<your_database_name>
    DB_USER=<your_mysql_username>
    DB_PW=<your_mysql_password>

####  _Replace_ 
<your_database_name>,
<your_mysql_username>, and 
<your_mysql_password> 
with `your` own values.


  ## [API Routes](#API-Routes)

`Make requests to these routes using a tool like Insomnia Core or any other API client`

The following routes are available in the API:

    GET /api/categories - Get all categories with associated products.

    GET /api/products - Get all products with associated category and tags.

    GET /api/tags - Get all tags with associated products.

    POST /api/categories - Create a new category.

    POST /api/products - Create a new product with associated category and tags.

    POST /api/tags - Create a new tag.

    PUT /api/categories/:id - Update a category by ID.

    PUT /api/products/:id - Update a product by ID with associated category and tags.
    
    PUT /api/tags/:id - Update a tag by ID.
    
    DELETE /api/categories/:id - Delete a category by ID.
    
    DELETE /api/products/:id - Delete a product by ID.
    
    DELETE /api/tags/:id - Delete a tag by ID.


## Contributing
Contributions to this project are welcome! If you find any issues or would like to suggest enhancements, please submit a pull request.


  ## [Feedback and Questions](#table-of-contents)

  To contact me please utilize the provided links below:

  [GitHub](https://github.com/skye143)
  
  [LinkedIn](https://www.linkedin.com/in/skye-h-988a7a221)

  [Email](mailto:skyeheredia@gmail.com)

