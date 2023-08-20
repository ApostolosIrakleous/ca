# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Clone repo
git@github.com:ApostolosIrakleous/ca.git

### `Setup MongoDB`
Atlas Cloud MongoDB
Create database at https://cloud.mongodb.com
In .env file update MONGODB_URI=mongodb+srv://your-db-connection

## Available Scripts

In the project directory, you can run:

### `Run Backend`
$ cd ca/backend
$ npm install
$ npm start

### `Run Frontend`
# open new terminal
$ cd ca (frontend)
$ npm install
$ npm start

### Seed Users and Products
Run this on browser: http://localhost:5000/api/seed
It returns admin email and password and sample products

### Admin Login
Run http://localhost:3000/signin
Enter admin email and password and click signin
