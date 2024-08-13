# Guestara Menu Management Application

This is a Node.js backend application for menu management. It allows you to create, read, update, and delete categories, subcategories, and items in a menu.

## Prerequisites

- Node.js 
- MongoDB 

## Getting Started

### 1. Clone the repository:

git clone https://github.com/your-username/Guestara-Task.git

### 2. Install the dependencies:

cd Guestara-Task
npm install

### 3. Set up the environment variables:

Create a `.env` file in the root directory and add the following variables:  
MONGODB_URI="connection-string-here"

Replace the `MONGODB_URI` value with your MongoDB connection string.

### 4. Start the application:

The server will start running on `http://localhost:3000`.

## API Documentation

You can test the API's by visiting `http://localhost:3000/api-docs` after starting the server.

## Database Choice

MongoDB has been selected for this project due to its flexibility as a NoSQL database, which is well-suited for managing hierarchical data like categories, subcategories, and items. Additionally, MongoDB’s seamless integration with Node.js and its powerful querying capabilities make it an ideal choice for this application.


## Learnings

1. Integrating Swagger for API Documentation and Testing
2. Managing hierarchical data structures in a database.
3. Crafting a README file and API documentation to provide a clear overview of the project.

## Difficulties
The most challenging aspect of the project was setting up the relationships between the various models (Category, SubCategory, and Item).  and ensuring proper data retrieval like retriving items of Categories.

## Future Improvements

Given more time, I would have implemented additional features such as introducing different user roles (e.g., admin, editor, viewer) with specific permissions to enhance security and ensure that only authorized users can perform certain actions.
Also, implement API rate limiting to prevent abuse by limiting the number of requests a user can make within a certain timeframe, enhancing both security and performance.




