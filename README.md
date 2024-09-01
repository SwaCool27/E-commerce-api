<h1>E-Commerce API</h1>

<h3>Description</h3>

This project is an e-commerce REST API built using Node.js and Express. The API provides functionalities such as managing products, handling user authentication, processing orders, and managing shopping carts. The application uses MongoDB as its database and includes features such as JWT-based authentication, data validation, and error handling.
Features


    -User Authentication: Sign up, log in, and secure routes with JWT.
    -Product Management: CRUD operations for products.
    -Order Management: Create and track orders.
    -Shopping Cart: Add, update, and remove items from the cart.
    -Category Management: Manage product categories.


<h3>Installation</h3>

  Clone the repository:

bash

git clone https://github.com/your-username/your-repo-name.git

Navigate to the project directory:

bash

cd your-repo-name

Install dependencies:

bash

yarn install

Set up environment variables by creating a .env file in the root directory:

bash

MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=your_client_url

Start the server:

bash

yarn start

Set up environment variables by creating a .env file in the root directory:

bash

MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=your_client_url

Start the server:

bash

    yarn start

Usage

    -API Endpoints: Detailed documentation of available endpoints can be found in the docs directory.
    -Testing: Use tools like Postman or Insomnia to interact with the API.

<h3>Technologies Used</h3>

    -Node.js
    -Express.js
    -MongoDB
    -Mongoose
    -JWT for Authentication
    -Yarn for Package Management

