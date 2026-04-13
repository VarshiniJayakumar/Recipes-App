# Recipes App

A CRUD application for managing recipes using Node.js, Express.js, and MongoDB (Mongoose).

## Features
- Create a new recipe
- Retrieve all recipes
- Retrieve a recipe by ID
- Update a recipe by ID
- Delete a recipe by ID

## Tech Stack
- Node.js
- Express.js
- MongoDB with Mongoose
- Postman for API documentation

## Setup
1. Clone the repository
2. Run `npm install`
3. Start MongoDB locally (`mongodb://localhost:27017/recipesDB`)
4. Run `node server.js`
5. Test endpoints with Postman

## API Endpoints
- `POST /api/recipes` → Create recipe
- `GET /api/recipes` → Get all recipes
- `GET /api/recipes/:id` → Get recipe by ID
- `PUT /api/recipes/:id` → Update recipe
- `DELETE /api/recipes/:id` → Delete recipe
