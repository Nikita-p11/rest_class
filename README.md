**Quora Post RESTful API**

## Project Overview

A simple RESTful API using Node.js, Express.js, and EJS, storing posts in an array instead of a database.

## Features

-> Create, Read, Update, Delete (CRUD) posts

-> Minimal setup with in-memory storage

-> Simple and lightweight API

## Technologies Used

-> Backend: Node.js, Express.js

-> Templating Engine: EJS

-> Storage: JavaScript Array (in-memory)

## Installation & Setup

# Clone the repository
git clone https://github.com/your-username/rest_class.git
cd rest_class

# Install dependencies
npm install

# Run the application
nodemon app.js

# Access the app
http://localhost:8000

## API Endpoints

GET     /posts        -> Get all posts
POST    /posts        -> Create a new post
GET     /posts/:id    -> Get post by ID
PUT     /posts/:id    -> Update a post
DELETE  /posts/:id    -> Delete a post

## Example Requests

**Create Post**
{
  "title": "How to learn JavaScript?",
  "content": "Start with the basics, practice coding, and build projects."
}

**Update Post**
{
  "title": "Updated Title",
  "content": "Updated content."
}

## Future Enhancements

-> Add database (MongoDB/MySQL)
-> Implement user authentication
-> Improve frontend UI
