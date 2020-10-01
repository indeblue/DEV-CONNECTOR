# DEV-CONNECTOR

This is developer platform, In which developer can connect to each other.This is a small social network app that includes authentication, profiles .
### Steps to run 

First go ahead and clone this repository either by downloading the .ZIP file or by entering `https://github.com/petercr/dev-connector.git` into your terminal.

Next to install the dependancies and run this project requires [Node JS & NPM package manager](https://www.nodejs.org) version 10 or higher.

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

This project also requires a MongoDB database or other NoSQL database in order to store the user & posts data. In order to connect this project to a MongoDB database follow the instructions below.

You will need to create a keys.js in the server config folder with

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```
![Annotation 2020-08-08 140529](https://user-images.githubusercontent.com/42699221/89706205-171ce680-d981-11ea-80c4-51a84a2c1891.png)

