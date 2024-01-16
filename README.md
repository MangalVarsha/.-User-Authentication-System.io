# .-User-Authentication-System.io
![image](https://github.com/MangalVarsha/.-User-Authentication-System.io/assets/88738232/8f47ea7e-9604-452b-bf98-882425bf2508)
# Welcome to MERN Login System
Hello everyone, In this project, we are going to create MERN Stack App with Login System. We will take a look at how to create login, registration, profile, reset password routes and learn how to send Mail from the Node.js backend application.

# Working with the Project
Download this project from above link. Create two configaration files into the project. First in the client and second in the server.
In the Client Folder create .env file and put this code inside it.
.env
REACT_APP_SERVER_DOMAIN='<server_domain>' # example 'http://localhost:8080'
Minimal full-stack MERN app with authentication using passport and JWTs.

# mern-auth

![Final App](https://i.postimg.cc/tybZb8dL/final-MERNAuth.gif)
Minimal full-stack MERN app with authentication using passport and JWTs.

This project uses the following technologies:

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for frontend
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend
- [MongoDB](https://www.mongodb.com/) for the database
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components


## Configuration

Make sure to add your own `MONGOURI` from your [mLab](http://mlab.com) database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```

## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```



