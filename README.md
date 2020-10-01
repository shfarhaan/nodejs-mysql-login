# Creating a Nodejs mySQL Login Tutorial

## We are going to need:

1. XAMP to be installed to run mysql Server
2. VS Code or any development environment
3. GIT for version controling
4. We need to have nodejs installed in our machine

### Now Open VS Code in a new window

Open an integrated terminal and create a package.json file
> $ npm init -y
It is going to store all dependencies and all related information to our project

### Next we are going to install 
   1. express (to start our server), 
   2. mysql (to connect nodejs to mysql server),
   3. dotenv (to store and protect sensitive information such as passwords and so on)
   4. hbs or handlebars (Our template for the html part)

#### Now in terminal write 
> $ npm install express mysql dotenv hbs

#### Next install nodemon so whenever we do any changes the server will restart automatically
> $ npm i --save nodemon 

> ###               "app.js" 

    const express = require("express")