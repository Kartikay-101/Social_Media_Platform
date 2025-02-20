# Social Media Platform - MERN Stack

## **Project Overview**
The **Social Media Platform** is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## **Step 1: Initializing the Project**
```bash
npm init -y
```
## **Step 2: Installing Required Packages**
```bash
npm i -g nodemon
npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
```
**2.1 Global Installation:**
```bash
npm i -g nodemon
Installs nodemon globally to automatically restart the server on code changes.
```
**2.2 Backend Dependencies:**
npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose

Package                 | Description
------------------------|---------------------------------------------------------
express                | A minimal and flexible Node.js web framework used for building the API.
body-parser            | Middleware to parse incoming request bodies (e.g., JSON, URL-encoded data).
bcrypt                 | A library for hashing passwords securely before storing them in the database.
cors                   | A middleware to enable Cross-Origin Resource Sharing, allowing the frontend to communicate with the backend.
dotenv                 | Loads environment variables from a .env file, keeping sensitive data secure.
gridfs-stream         | Enables handling large file uploads by storing them in MongoDB GridFS.
multer                 | Middleware for handling multipart/form-data, mainly used for uploading images or other files.
multer-gridfs-storage  | An extension of multer for storing uploaded files directly in MongoDB GridFS.
helmet                 | Helps secure Express apps by setting HTTP headers to prevent security vulnerabilities.
morgan                 | HTTP request logger for debugging and monitoring API requests.
jsonwebtoken           | Used for generating and verifying JSON Web Tokens (JWT) for user authentication.
mongoose               | An Object Data Modeling (ODM) library for MongoDB, providing a schema-based solution for managing database models.