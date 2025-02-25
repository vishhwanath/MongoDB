# MongoDB

MERN Ecommerce Application
Currently under construction for additional features

Description
Full-stack ecommerce application built with MERN stack. This project has two features:

Buyers register and browse the marketplace while interacting with products across different categories.
Admins control and manage the marketplace items and customer acounts.
Getting Started
Dependencies
Nodejs - The runtime environment of the application
Reactjs - Component based UI library
MongoDB - NoSQL database
Expressjs - Framework to handle routes and requests
Mongoose - MongoDB object modeling tool to model the database schema
Installation
After you cloned the repository do not start the application. To run the application fully you need to create a database and collection and provide your own database URI.

Setup
Go to MongoDB website and create a database and a collection named 'Items' and insert the data in the server/ItemsCollection.js file as a document.
Create a .env file in the server folder and type the following
    NODE_ENV = development
    PORT = 5000
    MONGO_URI = mongodb+srv://<your uri from mongodb website>
Running
After this you can run the project locally:

To run the front end
cd client
npm start
To run the back end
cd server
npm run dev TIP: Run both in split terminal so that you can see both ends running
Languages and tools
Node
React
Expressjs
Mongoose
Material UI
