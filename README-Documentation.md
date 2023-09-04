# B8IT150 Advanced Programming B8IT150

### Course : B8IT150 Advanced Programming 
### Lecturer : Paul Laird

### Student Name : Apostolos Irakleous 
### Student Number : 10611069

# Table of Contents
- 1.Overview
- 2.Goal
- 3.Contributions

### Overview
Creating an Information System of an e-Commerce web application for a company that sells Greek products as a gift hamper. The method used to create this application is MERN stack, that is a web development framework made up of the stack of MongoDB, Express. js, React. js, and Node.js. As any programming language was free to use for this assignment, I choose the above, to challenge myself for the creation of the information system 

### Goal
The goal of the project is to create a functional e-Commerce client-server web application. The project ties together the skills that have learnt during the B8IT150 lectures, with the combination of previous modules.
### 2.1 Aim
The aim of this project is to design and build an e-Commerce web application for the sale of Greek gifts for customers worldwide.
 
### 2.2 Objectives
The objective of the project is to provide a web application where customers can browse, select,(add to basket) and purchase a product. New users can register for an account. Customer order history can be viewed. Customers will also be able to browse items(search) in the catalog then select, add to a shopping cart and checkout the items for purchase.Enter details for shipping than the shopping functionality with integration with a payment gateway. 
Products will load fast and be responsive on all types of devices and scalable as more products are added or edit/delete by admin.Admin will be able to see order status /history/payment able to mark delivery.
### 2.3 Tools installed










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
## open new terminal
$ cd ca (frontend)
$ npm install
$ npm start

### Seed Users and Products
Run this on browser: http://localhost:5000/api/seed
It returns admin email and password and sample products

### Admin Login
Run http://localhost:3000/signin
Enter admin email and password and click signin
