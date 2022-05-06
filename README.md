# Basic Mern Stack Portfolio
This Git Repo contains final project for my Web Development course for the Fall of 2022. In this project I used React to create the client side with Material UI components. While the backend uses express, nodejs and Mongodb. The web app is a Portflio app for myself that contains a blog, my resume , and other stuff about me. On top of that I used the backend to send the name, email, and a message from a front-end form to the database hosted on MongoDB Atlas. 

## Cloning 
To clone this project and to run it on your own machine, you will have to take a few steps.

1. Clone the project using ``` git clone https://github.com/Hindesj/Final-Project```

2. In the repo you will see two separate directories. 
```
/client
/server
```
In the server directory you are going to want to create a config.env file
- This is where the URI to the MongoDB database will live
- it will look something like this.
```
ATLAS_URI = mongodb+srv://<USERNAME>:<PASSWORD>@mern.lmmyr.mongodb.net/<DATABASENAME>?retryWrites=true&w=majority
PORT=5001
```
- You can this connection info on the MongoDB Atlas page when creating the database

3. Once you have all that informaion run the following commands in the directories as follows.

```
/server $ node server.js
/client $ npm run start
```
When the server connection is successful there should be message stating that the connection has been established.
The Client should act the same way.

This is a bare minimum project and it should be treated as a jumping off point for future projects.