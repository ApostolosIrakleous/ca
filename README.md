
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
- Mongoose(npm install mongoose)
- Dotenv(npm install dotenv)



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
this install is for when ever we do a change in the database the server will restart and apply the changes.
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
#### Use of React Context 
is a method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree.




### 4.6 `Setup MongoDB`
Atlas Cloud MongoDB
Create database at https://cloud.mongodb.com
Connecting to MongoDB
First, we need to define a connection. If your app uses only one database, you should use mongoose.connect. If you need to create additional connections, use mongoose.createConnection.

Once connected, the open event is fired on the Connection instance. If you're using mongoose.connect, the Connection is mongoose.connection. Otherwise, mongoose.createConnection return value is a Connection.
In .env file update MONGODB_URI=mongodb+srv://your-db-connection. Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/b9ad1e13-ec1f-42a7-aa79-2b19d542c22d)


### 5.0 User inderface and User Experience
The user interface (UI) is the point of human-computer interaction and communication in a device. This can include display screens, keyboards, a mouse and the appearance of a desktop. It is also the way through which a user interacts with an application or a website.User Experience refers to the feeling users experience when using a product, application, system, or service. It is a broad term that can cover anything from how well the user can navigate the product, how easy it is to use, how relevant the content displayed is etc.

## 5.1 How to Run the application

In the project directory, you can run:

### `Run Backend`
$ cd ca/backend
$ npm start

### `Run Frontend`
## open new terminal
$ cd ca (frontend)
$ npm start

### 5.2 Homescreen
This is what a user as an admin looks when the application starts, a navigation bar on the left, search bar, cart, logged user, a display of featured products where you can interact with:
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/e64e8ea7-bc50-4056-a115-2f6bdfa939eb)
Inside of a product page you can see the name of the product , the description, the price, reviews, status, cart button, you can interact with all of them.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/04676507-ee0d-4f0f-859b-ae94c7c6f1bd)

#### 5.3 As an admin user when you click admin:
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/e01eb583-01e0-4555-9f89-d356f878955b)

- you can see admin's dashboard with the sales of the shop.
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/82bd96f6-07ca-40f3-a5e4-d257955b8233)

- Product page where as an admin you can created a new product, edit or delete one!
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/3cd14e8d-971e-4548-97d1-76181f30633a)



- you will get the above notification when a successfull change is made.
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/488256d7-e07a-4b93-90ca-2d58fd6a5c6b)

- Order screen withs details of a costumer's order.
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/bfbe67ad-f635-4946-b5b1-f9c3d7da6e6b)

- User screen where as an admin, you can see the users id using the app. you can delete or edit same
![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/d4bdf26f-7939-4650-92a3-e6a4383180b4)


### 5.4 As a costumer user
when you add a product to the cart will look like this:![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/c5e7518c-a825-4185-81b9-3a642e07a87a)
- Than will be 2 options sign up or sign in:
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/bc3f934b-3ce7-4426-9ec4-fbf97dc1910b)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/106c9863-47ea-429b-857f-bc1fb18e26c4)

A shopping cart screen where you can interact with: add/ remove item , delete order and checkout
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/f8ff099c-b5be-4e2e-9504-814b9e522e39)

A Shipping address screen after checkout :
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/2ef88a05-0c54-41bf-b2ef-cadcc8f87e1a)

A Payment method screen and preview order screen:
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/f5fb98a8-7324-4052-b51a-02c400c805dc)
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/7f67168d-64ad-47be-b613-2f4bedc0aae7)

Order summary screen:
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/0e9d82f7-b3b2-46b5-acb5-f45c06cbe5b8)

If you pay the order you will get a paid notification"
- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/fafb4d09-606e-4ea8-96bf-1b05600e5db1)

- ![image](https://github.com/ApostolosIrakleous/ca/assets/132573422/2406e82a-35a4-46cb-ab44-0b546a312b22)


### other helpfull informations

### Admin Login
Run http://localhost:3000/signin
Enter admin email and password and click signin







#### Clone repo git@github.com:ApostolosIrakleous/ca.git
# References
- https://www.geeksforgeeks.org/what-is-react-router-dom/
- https://www.youtube.com/@NetNinja (frontend, how to built with express and mongo db)
- https://www.youtube.com/@freecodecamp (MERN Stack Tutorial)
- https://www.youtube.com/@CodingWithChaim(Work With Hooks,useSate as well as useEffect)
- https://www.youtube.com/@CodingwithBasir(Bootstrap and React Routing Tutorial)
- https://www.youtube.com/@javascriptmastery(MERN stack tutorial)
- https://www.techtarget.com/whatis/definition/Nodejs#:~:text=js%20(Node)%3F-,Node.,to%20learn%20an%20additional%20language.
- https://www.upgrad.com/blog/http-requests-with-axios-npm/
- https://react-bootstrap.netlify.app/
- https://www.techtarget.com/whatis/definitions/S
- https://www.productplan.com/glossary/user-experience/#:~:text=Definition%3A%20User%20Experience%20refers%20to,the%20content%20displayed%20is%20etc.
