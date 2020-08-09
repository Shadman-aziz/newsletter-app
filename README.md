# newsletter-app
a newsletter app template made using node js

steps to setup:

1. Cd into location where you want to make project ex. Mkdir Newsletter-Signup
2. Cd into it and make app.js file ex. Cd Newsletter-Signup, touch app.js
3. Make whatever other files you need ex touch signup.html success.html failure.html
4. Initialize npm. Ex npm init
5. Install npm modules needed ex. Npm install body-parser express request
6. Open atom and “require” the modules in 5
7. Copy this into the top of your app,js file 

//jshint esversion:6
const express = require("express");
const bodyParser = require("body-parser");
const request = require("request");

const app = express();

app.listen(3000,function(){
  console.log("fun");
})

