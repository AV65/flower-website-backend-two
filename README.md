# flower-website-backend-two


A RESTful API built with **Node.js**, **Express.js**, and **MongoDB**, designed to support the backend of an online flower store. This API manages flower listings, image uploads, category classification, and user authentication (signup & login).

---

## Table of Contents

- Overview
- Features
- Live Demo
- Presentation Link
- Technologies Used
- API Endpoints
- Installation & Setup
- Environment Variables 
- Author
- License

##  Overview

The Flower Website Backend is a complete API server to manage an online flower shop's products and users. It includes:

- Full CRUD operations on flower entries
- Image upload support
- Category tagging
- Secure user registration and login
- Validation and error handling


##  Features

-  RESTful API with Express
-  MongoDB integration using Mongoose
-  Flower CRUD (Create, Read, Update, Delete)
-  Image upload via `multer`
-  User authentication with hashed passwords
-  Strong password & email validation
-  Error handling middleware
-  Environment configuration using `dotenv`

## Live Demo
[Live demo](https://flower-website-backend-two-2.onrender.com)

## Presentation Link
[Presentation Link](https://www.loom.com/share/e3bc650da79d444ca0675375ec3c3df8?sid=5c99c623-0140-4b54-9427-b4b078aea5ab)
##  Technologies Used

- Node.js
- Express.js
- MongoDB + Mongoose
- Multer (image uploads)
- Bcrypt (password hashing)
- Validator (email & password validation)
- Dotenv (environment variables)


##  API Endpoints

The API will be running on http://localhost:5000

###  Auth
- POST /api/users/signup — Register a new user  
- POST /api/users/login — Log in existing user
- GET /api/users/getusers — Shows all the registered users


###  Flowers
- GET /api/flowers — Get all flowers  
- GET /api/flowers/:id — Get a flower by ID  
- POST /api/flowers — Create a new flower (image upload supported)  
- PATCH /api/flowers/:id — Update a flower  
- DELETE /api/flowers/:id — Delete a flower  


##  Installation & Setup

1. **Clone the repository:**

2. **Install dependencies:**

3. **Set up the environment variables:**
   PORT=5000
   MONGO_URI= mongodb+srv://mfthegreat301:g7Q9Xs2A0X0VNUZI@cluster0.imwxm.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
   SECRET = BEAPILOTORBENOTHING

4. **Start the server:**

## Environment Variables
Ensure you configure the `.env` file with the correct MongoDB connection string and port.

## Author 
  Name: Muhammad Farouk
  Contact: [salihiyaha4@gmail.com]
  GitHub: [AV65](https://github.com/AV65)

## License
This project is licensed under the MIT License.