# FullStack Social Media App

Build a COMPLETE Fullstack Responsive MERN App with Auth, Likes, Dark Mode | React, MongoDB, MUI

This repository contains the source code for a MERN (MongoDB, Express, React, Node.js) based responsive social media website.
The project includes both server-side (backend) and client-side (frontend) development.
Getting Started
Backend Installation and Configuration
Clone the repository:
Install Global Dependencies
npm i -g nodemon

Install Backend Dependencies
npm init -y npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose

Configure Package.json for ES6 Modules
echo '{"type": "module"}' > package.json

Setup MongoDB Database
Create a MongoDB database and update the .env file:
echo "MONGODB_URI=your-mongodb-uri\nJWT_SECRET=your-jwt-secret\nPORT=3001" > .env

Organize code into folders for clear structure.
Start Backend Server
node index.js

Frontend Installation and Configuration
Create React App
npx create-react-app client

Install Frontend Dependencies
cd client npm i react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material

Create JSConfig for Better Imports
echo '{"compilerOptions": {"baseUrl": "src"}}' > jsconfig.json

Redux Toolkit Configuration

Set up Redux Toolkit for state management.

Routing Setup

Implement routing using react-router-dom@6.

Testing, Documentation, and Deployment
Test functionalities, document API endpoints, and deploy both backend and frontend as needed.

Additional Considerations
Version Control (Git)

Initialize a Git repository, commit the initial setup, and push to a remote repository (e.g., GitHub).

Environment Variables
Keep sensitive information in the .env file for security.


Documentation
Document API endpoints, testing practices, and any other relevant information.


Error Handling and Logging
Implement robust error handling on both server and client sides.


Responsive Design
Ensure the website is responsive for various devices.




![bandicam 2024-02-09 12-23-33-804](https://github.com/shubhamdev123/SociopediaMERNStack/assets/96860714/05e42603-6db7-40ed-9c95-e675427283c0)
![bandicam 2024-02-09 12-26-02-284](https://github.com/shubhamdev123/SociopediaMERNStack/assets/96860714/4a9655d1-7043-4b2b-9a66-e7bb1abd4dee)
![bandicam 2024-02-09 12-26-06-650](https://github.com/shubhamdev123/SociopediaMERNStack/assets/96860714/e53b68f7-ac0b-49d7-97d3-02e1efcd521c)
![bandicam 2024-02-09 12-26-18-035](https://github.com/shubhamdev123/SociopediaMERNStack/assets/96860714/cf245df3-785e-46ec-a5fb-ae04d02ad1c9)
![bandicam 2024-02-09 12-26-37-698](https://github.com/shubhamdev123/SociopediaMERNStack/assets/96860714/dc2077d0-b691-4a45-a7d1-d6d36b1864ba)


 
