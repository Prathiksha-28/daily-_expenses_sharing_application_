# daily-_expenses_sharing_application_
## Description
A backend service for managing daily expenses and splitting them among users.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (optional)

## Setup Instructions
1. Clone the repository.
2. Install dependencies:

   npm install
3. Set up environment variables (e.g., MongoDB URI).
4. Start the application:

   npm start
   
## API Endpoints
- `POST /users`: Create a user.
- `GET /users/:id`: Retrieve user details.
- `POST /expenses`: Add an expense.
- `GET /expenses/user/:id`: Retrieve user expenses.
- `GET /expenses`: Retrieve all expenses.
- `GET /expenses/download`: Download the balance sheet.

## Testing
Run tests using:

  npm test
  
## License
MIT License


