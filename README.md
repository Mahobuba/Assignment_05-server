# Technology Used:
-> Nodejs -> Express -> MongoDB

# Set Up Environment Variables
For security purposes, all sensitive information (such as MongoDB credentials) should be stored in a .env file.

- Create a .env file
In the root directory of your project, create a .env file.
Add the following configuration variables to the .env file:

- DB_USER=your-mongodb-username
- DB_SECRET=your-mongodb-password

- MongoDB URI as -> mongodb+srv://${DB_USER}:${DB_SECRET}@cluster0.mongodb.net/myDatabase?retryWrites=true&w=majority (Use your URI)
