# Social Media Platform - MERN Stack

## **Project Overview**
The **Social Media Platform** is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This project aims to provide users with a secure and interactive platform to share posts, connect with others, and engage in meaningful conversations.

## **Step 1: Installing Required Packages**
To set up the backend for the Social Media Platform, run the following command in your terminal:

```bash
npm i -g nodemon
npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
1.1 Global Installation:
npm i -g nodemon
Installs nodemon globally. It automatically restarts the server when changes are detected in the code, making development more efficient.
1.2 Backend Dependencies:
Package	Description
express	A minimal and flexible Node.js web framework used for building the API.
body-parser	Middleware to parse incoming request bodies (e.g., JSON, URL-encoded data).
bcrypt	A library for hashing passwords securely before storing them in the database.
cors	A middleware to enable Cross-Origin Resource Sharing, allowing the frontend to communicate with the backend.
dotenv	Loads environment variables from a .env file, keeping sensitive data secure.
gridfs-stream	Enables handling large file uploads by storing them in MongoDB GridFS.
multer	Middleware for handling multipart/form-data, mainly used for uploading images or other files.
multer-gridfs-storage	An extension of multer for storing uploaded files directly in MongoDB GridFS.
helmet	Helps secure Express apps by setting HTTP headers to prevent security vulnerabilities.
morgan	HTTP request logger for debugging and monitoring API requests.
jsonwebtoken	Used for generating and verifying JSON Web Tokens (JWT) for user authentication.
mongoose	An Object Data Modeling (ODM) library for MongoDB, providing a schema-based solution for managing database models.```bash