# Expense-tracker
# Expense Tracker

This project is a web application for managing personal expenses using Node.js, Express, and MySQL.

## Project Setup

1. Clone the repository
2. Run `npm install` to install dependencies
3. Configure MySQL database connection in `server.js`
4. Run `node server.js` to start the server

## Dependencies

- express
- mysql
- body-parser
- bcryptjs

## Functionalities

- User registration and login
- Adding expenses
- Viewing expenses
- Updating expenses
- Deleting expenses

## Instructions to Run the Application

1. Ensure MySQL server is running
2. Create `expense_tracker` database and tables using the provided SQL script
3. Run `node server.js` to start the server
4. Use an API client like Postman to interact with the endpoints

## Endpoints

- `POST /register` - Register a new user
- `POST /login` - Login a user
- `POST /expenses` - Add a new expense
- `GET /expenses/:user_id` - View expenses for a user
- `PUT /expenses/:id` - Update an expense
- `DELETE /expenses/:id` - Delete an expense
