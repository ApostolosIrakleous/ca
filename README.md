
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
- 4.Building

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
### 2.3 Tools installed on Windows
This project completed on visual studio code,in windows oparating system. Some tools had to be istalled prior starting this assignment, like nodejs for windows from this page: https://nodejs.org/en/download.
Next tool installed is Git for windows oparating system from https://git-scm.com/ so in my project i can use gitbash in windows(VSC)terminal.(like Linux line command).

#### `Version of tools used in my project`
$ git --version (to check my git version)
git version 2.41.0.windows.3

$ node --version (to check my node version)
v18.15.0

$ npm --version (to check my npm version)
9.5.0


# 3. Getting Started with Create React App
While we have VS code open, start a command line than create a folder where the app will be stored, type the command mkdir ca (where my app will be store)(we can change the title later) than we will go inside my folder (type) cd ca and create the app by typing the 
command npx create-react-app than by typing npm start the default broswer will open automatically the react app.(local host.3000). We can now change the header and stard coding!
For this assignment and proof of working with the project, we need to create a github folder, to push and commit changes of our code,plus sharing it to others. to do that we have two options: on source control button see image ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/01a0049f-0d20-4abd-93ec-2b0cb5b55cdb) either initialize repository or publish to Github.You need to create a Github account.

### 3.1 Tools installed on Visual Studio Code (VSC)
- ESLint
- JavaScript (ES6) code snippets
- VS code ES7 React/Redux/GraphQL/React-Native snippets
- Axios ($ npm install axios)
- React-bootstrap (npm install react-bootstrap bootstrap)
- Nodemon (npm intall nodemon --save -dev)



# 4. Building
### 4.1 `Adding page routing`
Using npm i react-router-dom is an npm package that enables you to implement dynamic routing in a web app. It allows you to display pages and allow users to navigate them. It is a fully-featured client and server-side routing library for React. React Router Dom is used to build single-page applications i.e. applications that have many pages or components but the page is never refreshed instead the content is dynamically fetched based on the URL. This process is called Routing and it is made possible with the help of React Router Dom.
routes created are:
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/55aceb9c-e699-4af8-92a2-edeb41997ccf)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/e38207ad-369b-42df-8be8-6bb742df5962)

### 4.2 `Create Node.JS Server` Backend
Node.js (Node) is an open source, cross-platform runtime environment for executing JavaScript code. Node is used extensively for server-side programming, making it possible to use JavaScript for client-side and server-side code.
install `npm init` after creating a backend folder in the main project.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/7aa2e39b-8403-4b41-a8ab-b6ccbbef1565) ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/f069bb4e-7113-4d36-ba75-a9ec6a2a7cfc)

create a file called server.js install ` npm install express`
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/cb918ba8-0589-4c24-9dad-d08d18b0411d)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/5e982aa2-2c26-4139-9ca5-21cdcc883c8a)

### 4.3 Restart server 
### `npm intall nodemon --save -dev`
this istall is for when ever we do a change in the database the server will restart and apply the changes.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/8d16f38d-e83c-4566-845c-42a8d0257d49)
#### if changes done in the app and file saved you will get this:
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/4354bde3-f3e1-4f91-bc99-77bf4745dbde)


### 4.4 fetch products from backend with Axios and Hooks
Axios is a robust JavaScript library that streamlines the process of making HTTP requests from web browsers or Node.js servers. It offers a promise-based interface, facilitating the handling of asynchronous tasks. Performing GET requests to fetch data from servers is a common task in web development. Axios, a widely-used JavaScript library, simplifies this process by offering an intuitive and efficient approach to handling GET requests. Hooks allow function components to have access to state and other React features. Because of this, class components are generally no longer needed.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/13dfd16d-a49b-4579-bca9-8fce7e6a3aac)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/65cda4f3-f33d-435d-b748-aac8f84efe8d)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/9f6c8670-e4a3-4939-8512-a10203d2bd76)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/dd8d5b23-739b-4ee6-8905-21f37699549e)


### Seed Users and Products
Run this on browser: http://localhost:5000/api/seed
It returns admin email and password and sample products



### 4.5 Components
A component is an independent, reusable bit of code which divides the UI(user inderface) into smaller pieces. For example, if we were building the UI of React website using Reactjs we can break its UI into smaller parts,Instead of building the whole UI under one single file like HTML, we can divide all the sections into smaller independent pieces. In other words, these are components. Each component will go into its own JavaScript file. 
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/07440733-192d-497d-b6ba-5889232141f1)


#### This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Clone repo
git@github.com:ApostolosIrakleous/ca.git

### `Setup MongoDB`
Atlas Cloud MongoDB
Create database at https://cloud.mongodb.com
In .env file update MONGODB_URI=mongodb+srv://your-db-connection

## How to Run the application

In the project directory, you can run:

### `Run Backend`
$ cd ca/backend
$ npm start

### `Run Frontend`
## open new terminal
$ cd ca (frontend)
$ npm start
### other helpfull informations


### Admin Login
Run http://localhost:3000/signin
Enter admin email and password and click signin
# References
- https://www.geeksforgeeks.org/what-is-react-router-dom/
- https://www.youtube.com/@CodingwithBasir
- https://www.techtarget.com/whatis/definition/Nodejs#:~:text=js%20(Node)%3F-,Node.,to%20learn%20an%20additional%20language.
- https://www.upgrad.com/blog/http-requests-with-axios-npm/
- https://react-bootstrap.netlify.app/
