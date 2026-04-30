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
1. Clone the repository.
2. Run `npm install`.
3. Create a `.env` file and add your `MONGO_URI` (either local or MongoDB Atlas).
   ```text
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. Run `npm start` (or `npm run dev` for nodemon).
5. Test endpoints with Postman.

## Deployment (Render)
- **Build Command**: `npm install`
- **Start Command**: `node server.js`
- **Env Variable**: Add `MONGO_URI` in the Render dashboard.

## API Endpoints
- `POST /api/recipes` → Create recipe
- `GET /api/recipes` → Get all recipes
- `GET /api/recipes/:id` → Get recipe by ID
- `PUT /api/recipes/:id` → Update recipe
- `DELETE /api/recipes/:id` → Delete recipe

## Sample Request Body (POST/PUT)
```json
{
  "title": "Spaghetti Carbonara",
  "ingredients": ["Pasta", "Eggs", "Cheese", "Guanciale"],
  "instructions": "Boil pasta. Mix eggs and cheese. Fry guanciale. Combine all."
}
```

