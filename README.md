# TutorialsLab
This is a full-stack web application that allows users to create accounts, log in, and log out. 
It uses React on the front-end and Node.js, Express, and MongoDB on the back-end along with jwt and google-oauth-20 for authentication.
Protected routes: Some routes require authentication. If the user is not authenticated, they will have to log in first .
Persistent login: If a user logs in and then closes the application, they will remain logged in when they reopen the application.
It also has a sign in with google method to sign in using google.
On the protected page data is displayed from mongodb database collection and once the user signup then all its data is saved in database.
Passwords are protected with bcrypt and important data with .env.
If an already registered user tries to register once again will get an error of "User already exists"

#Technologies Used
React: A JavaScript library for building user interfaces.
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
Express: A web framework for Node.js.
MongoDB: A NoSQL database that stores data in JSON-like documents.
JWT: JSON Web Tokens for authentication.
bcrypt:to hash password.
passportJs:to use google authentication
tailwind css:to apply styling to website

