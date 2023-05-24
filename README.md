# E-commerce Back End 

# Walkthrough  Video 
https://drive.google.com/file/d/1YiLDdXJyIobKa4LRfTfuB_tT5fFbPR7N/view

# Prerequisites
Node.js installed on your machine

MySQL server installed 

Insomnia Core 
 # Installation
Clone the repository from GitHub.
bash
Copy code
git clone https://github.com/TamaraDawg/EcommerceBackEnd
Navigate to the project directory.
bash:
Copy code
cd EcommerceBackEnd
Install the required dependencies.
bash:
Copy code
npm install
Create a new file named .env in the project's root directory and add the following environment variables:
makefile
Copy code
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password

Run schema file
bash
source schema.sql 
# Usage
Start the application by running the following command:
npm start
Once the server is running, the Sequelize models will be synced with the MySQL database.


Open Insomnia Core or a similar tool to test the API endpoints.

Use the following routes to interact with the data:

GET /api/categories: Retrieve all categories in a formatted JSON response.

GET /api/products: Retrieve all products in a formatted JSON response.

GET /api/tags: Retrieve all tags in a formatted JSON response.

POST /api/categories: Create a new category by sending the required data.

POST /api/products: Create a new product by sending the required data.

POST /api/tags: Create a new tag by sending the required data.

PUT /api/categories/:id: Update a category by specifying the category ID in the route parameter and sending the updated data.

PUT /api/products/:id: Update a product by specifying the product ID in the route parameter and sending the updated data.

PUT /api/tags/:id: Update a tag by specifying the tag ID in the route parameter and sending the updated data.

DELETE /api/categories/:id: Delete a category by specifying the category ID in the route parameter.

DELETE /api/products/:id: Delete a product by specifying the product ID in the route parameter.

DELETE /api/tags/:id: Delete a tag by specifying the tag ID in the route parameter.

