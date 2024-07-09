This is simple login and Signup page with Backend-ExpressJS and MongoDB Atlas using online mongodb.
Develop a real-world Forums application, a common use case in web development
Create and manage three distinct collections: "User," "Post," and "Comments" to handle different data types.
Describe the relationship between posts and comments within the application's data structure
Map application functionality to specific routes and control logic using controllers

To organize this data effectively, we'll create three new collections: "User," "Post," and "Comments."

steps 1 -> the current working directory is the root folder (you can give any name of the folder) StackUp-BackEnd-ExpressJS-Part-II.

Next, enter the following commands in your terminal.
commands follow :-
mkdir forum-app
cd forum-app
npm install bcryptjs body-parser dotenv ejs express express-session mongoose

**folder**:_
Within your project folder forum-app, we are going to create a new folder called **models**.
Next, in the same project folder, create a folder called **views** and another folder called **public**.
To create a reusable component, within the views folder, create a new folder called **components.** 
Next, in the same project folder, create 2 more folders, routes and controllers. 
correctly, your project folder forum-app should have six folders – **models, node_modules, public, routes, controllers and views, and two JSON files - package-lock.json and package.json**.

**Environment Variables**
Next, within the project folder, create a new file** .env.**
Now, copy the code below and add it to the .env file.
code put in .env file
db_connection="to_be_added_in_subsequent_steps"
PORT=3001

**Creating a Project on MongoDB** 
goto click here to link https://account.mongodb.com/account/register
 1. register you account 
 2.  click on 'Projects'
 3.  click on the 'New Project' button.
    
**Deployment of Database**
1. select the M0 FREE tier.--> You can name the cluster ForumCluster (you can give any name).
2. Once you are done, click on the Create Database User button.
3. Next, click on the Choose a connection method button.
In the modal, select the first option -- Drivers.
Then, replace the <password> in the connection string with the password from earlier.

**Running Our Code**
node app.js
In your browser, open localhost:3001 . 
 Thank you
