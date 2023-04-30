<!-- ABOUT THE PROJECT -->
# About The Project
![Screenshot 2023-04-22 at 5 30 06 PM](https://user-images.githubusercontent.com/115289871/235349017-ec17dc8b-0ed7-4617-ab39-93ab85a50663.png)






In this Project, I've built a WebApp namely Personal Blog Website using which you can publish your own blogs. This WebApp is extremely beneficial for journaling or documenting some kind of activity. So, just use it and have fun!!!



Use the `README.md` to get started.




# Built With

The Tech Stacks use are:

<div align="center">
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mongodb,expressjs,nodejs,js,ejs,css" />
</a>
</div>




<!-- GETTING STARTED -->
# Getting Started

To get started, create a file called app.js and import all the required modules in it. After that create a folder called views and place the about.ejs, compose.ejs, contact.ejs, home.ejs, and post.ejs files in it. Also, inside views folder create a sub-folder called partials in which include header.ejs and footer.ejs filed. After that, create another folder called public in which add another folder called css in which you'll need to add a file called styles.css.


* modules

  ```sh
  const express = require("express");
  const bodyParser = require("body-parser");
  const ejs = require("ejs");
  const _ = require("lodash");
  const mongoose = require("mongoose");
  ```

* ejs connectivity

  ```sh
  app.set("view engine","ejs")
  ```
  
* Using Body Parser

  ```sh
  app.use(bodyParser.urlencoded({extended: true}));
  ```

## Prerequisites

To begin with our Project, we'll need to install some npm packages like express, mongoose, body-parser, ejs, and lodash using the command given below. 


* npm

  ```sh
  npm install express mongoose ejs lodash body-parser
  ```
  
  
* To ease the process of development, we'll install nodemon (Make sure you already have nodemon installed in your system, if not then [visit here](https://nodemon.io/)).

  ```sh
  npm i nodemon
  ```


<!-- CONTACT -->
# Contact

Your Name - Shivank Kapur - shivankkapur2004@gmail.com

Project Link: 
