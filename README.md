# Car Management Application

## Overview

The **Car Management Application** is a full-stack web app that allows users to manage their car listings. Users can **sign up**, **log in**, and securely manage their car inventory by performing **CRUD operations** (Create, Read, Update, Delete). This application is built using **React.js** for the frontend and **Node.js** with **Express** for the backend, along with **MongoDB** for data storage.

The application also includes a **search functionality** for users to easily find cars based on keywords in the title, description, or tags. It is deployed with the frontend hosted on **Vercel** and the backend on **Heroku**.

---

## Features

- **User Authentication**: Secure sign-up and login with JWT (JSON Web Token) authentication.
- **Car Management**: 
  - Add new car listings with title, description, tags, and up to 10 images.
  - Edit and delete car listings.
- **Search Functionality**: Search through car listings by title, description, or tags.
- **Responsive UI**: Built with React.js for a dynamic, user-friendly interface.
- **CRUD Operations**: Backend implemented with Node.js and Express to handle API requests for cars and users.
  
---

## Technologies Used

- **Frontend**:
  - React.js
  - React Router for page navigation
  - Axios for making HTTP requests
  - CSS for styling
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB for data storage
  - JWT (JSON Web Token) for user authentication
- **Deployment**:
  - Frontend: Vercel
  - Backend: Heroku

---

## API Endpoints

### User Routes
- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Login an existing user and receive a JWT.

### Car Routes
- **GET /api/products**: Retrieve all cars for the logged-in user.
- **GET /api/products/:id**: Get details of a particular car.
- **POST /api/products**: Create a new car listing.
- **PUT /api/products/:id**: Update a specific car listing.
- **DELETE /api/products/:id**: Delete a specific car listing.

---

## How to Run the Project Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/car-management-app.git
   cd car-management-app
