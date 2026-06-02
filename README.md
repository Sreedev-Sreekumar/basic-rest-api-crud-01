# Basic REST API with CRUD Operations
# Internship - Prodigy InfoTech

This project was developed as part of my Backend Web Development Internship at Prodigy InfoTech.

---

## Objective

The objective of this project is to build a basic REST API using Node.js and Express.js that performs CRUD (Create, Read, Update, Delete) operations on user data.

---

## Technologies Used

- Node.js
- Express.js
- JavaScript
- Postman
- Visual Studio Code

---

## Features

- Create new users
- Get all users
- Get user by ID
- Update user details
- Delete users
- Input validation
- Error handling

---

## API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /users | Create user |
| GET | /users | Get all users |
| GET | /users/:id | Get user by ID |
| PUT | /users/:id | Update user |
| DELETE | /users/:id | Delete user |

---

## Sample Request Body

```json
{
  "id": 1,
  "name": "Sreedev",
  "email": "sreedev@gmail.com",
  "age": 21
}
```

---

## Validation Implemented

- Name should not be empty
- Email should contain "@"
- Age should be valid

---

## Testing

All API endpoints were tested successfully using Postman.

---

## Learning Outcome

Through this project, I gained practical knowledge of:

- REST APIs
- CRUD Operations
- Express.js Routing
- Request & Response Handling
- Validation
- API Testing using Postman
- Backend Development Concepts

---

## Internship Details

Backend Web Development Internship  
Prodigy InfoTech
