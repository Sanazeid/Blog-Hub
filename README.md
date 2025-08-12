# Blog-Hub

A fullstack-style blogging platform built with Node.js and Express, featuring a RESTful backend API and a server-rendered frontend using EJS templates.

---

## Overview

Blog Hub demonstrates a clear separation between frontend and backend layers:

- **Backend:** Provides a REST API to manage blog posts (create, read, update, delete)  
- **Frontend:** Renders views with EJS templates and interacts with the backend API using Axios  

**Note:** Data is stored **in-memory** on the backend, so it resets every time the server restarts. This simplifies the setup for learning and prototyping, but does not provide persistent storage. Adding a database is a natural next step to make it fully persistent.

This project is ideal for learning Express.js fundamentals, REST API design, server-side rendering, and client-server communication.

---

## Technologies

- Node.js  
- Express.js  
- body-parser  
- axios  
- EJS templating engine
- css

---

## Features

- Create, read, update, and delete blog posts
- Frontend server renders dynamic pages with EJS templates
- Frontend communicates with backend via REST API using Axios
- In-memory data store (resets on backend restart) for simplicity.

  ---

## Running the Project

- Start the backend API server (runs on port 4000):
cd backend
node index.js

- Start the frontend server (runs on port 3000):
  cd frontend
  node index.js

- Open your browser and go to http://localhost:3000 to use the app

