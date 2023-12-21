# MERN Estate App

## Overview

**mern-estate** is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, and Node.js). This application serves as a foundation for a real estate platform, allowing users to manage properties, user accounts, and authentication.

## Installation

Before running the application, make sure you have Node.js and npm installed on your machine. Follow these steps to set up the project:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mern-estate
   ```
   
2. Install dependencies:

```bash
npm install
npm install --prefix client
npm run build --prefix client
```

Configuration
Make sure to set up your environment variables. Create a .env file in the root of the project and configure the following variables:

```env

MONGODB_URI=<your-mongodb-uri>
SECRET_KEY=<your-secret-key>
```
Usage Development
To run the application in development mode with automatic server restarts, use:

```bash

npm run dev
```
This command uses nodemon to watch for changes in the server files.


Production
For a production environment, start the application using:

```bash

npm start
```
Dependencies:
bcryptjs: Library for hashing passwords securely.
cookie-parser: Middleware for parsing cookies in Express.
dotenv: Module for loading environment variables from a .env file.
express: Web application framework for Node.js.
jsonwebtoken: Library for creating JSON Web Tokens (JWT) for user authentication.
mongoose: MongoDB object modeling for Node.js.
nodemon: Utility to automatically restart the server during development.
