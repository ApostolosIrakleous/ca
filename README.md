
# B8IT150 Advanced Programming B8IT150!
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/3ce29f61-07d3-41e9-862f-01735778e087)


### Course : B8IT150 Advanced Programming 
### Lecturer : Paul Laird

### Student Name : Apostolos Irakleous 
### Student Number : 10611069

# Table of Contents
- 1.Overview
- 2.Goal
- 3.Getting Started

### Overview
Creating an Information System of an e-Commerce web application for a company that sells Greek products as a gift hamper. The method used to create this application is MERN stack, that is a web development framework made up of the stack of MongoDB, Express. js, React. js, and Node.js. As any programming language was free to use for this assignment, I choose the above, to challenge myself for the creation of the information system.
<img width="960" alt="MERN-part-1" src="https://github.com/ApostolosIrakleous/ca/assets/132573422/e838a07e-59ba-4eb0-a5cc-efa8ccaddd52">


### Goal
The goal of the project is to create a functional e-Commerce client-server web application. The project ties together the skills that have learnt during the B8IT150 lectures, with the combination of previous modules.
### 2.1 Aim
The aim of this project is to design and build an e-Commerce web application for the sale of Greek gifts for customers worldwide.
 
### 2.2 Objectives
The objective of the project is to provide a web application where customers can browse, select,(add to basket) and purchase a product. New users can register for an account. Customer order history can be viewed. Customers will also be able to browse items(search) in the catalog then select, add to a shopping cart and checkout the items for purchase.Enter details for shipping than the shopping functionality with integration with a payment gateway. 
Products will load fast and be responsive on all types of devices and scalable as more products are added or edit/delete by admin.Admin will be able to see order status /history/payment able to mark delivery.
### 2.3 Tools installed
This project completed on visual studio code,in windows oparating system. Some tools had to be istalled prior starting this assignment, like nodejs for windows from this page: https://nodejs.org/en/download.
Next tool installed is Git for windows oparating system from https://git-scm.com/ so in my project i can use gitbash in windows(VSC)terminal.(like Linux line command).

#### `Version of tools used in my project`
$ git --version (to check my git version)
git version 2.41.0.windows.3

$ node --version (to check my node version)
v18.15.0

$ npm --version (to check my npm version)
9.5.0

### 2.4 Tools installed on Visual Studio Code (VSC)
- ESLint
- JavaScript (ES6) code snippets
- VS code ES7 React/Redux/GraphQL/React-Native snippets


# 3. Getting Started with Create React App
While we have VS code open, start a command line than create a folder where the app will be stored, type the command mkdir ca (where my app will be store)(we can change the title later) than we will go inside my folder (type) cd ca and create the app by typing the 
command npx create-react-app than by typing npm start the default broswer will open automatically the react app.(local host.3000). We can now change the header and stard coding!
For this assignment and proof of working with the project, we need to create a github folder, to push and commit changes of our code,plus sharing it to others. to do that we have to options: on source control button see image ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/01a0049f-0d20-4abd-93ec-2b0cb5b55cdb) either initialize repository or publish to Github.You need to create a Github account.

#### This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
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
