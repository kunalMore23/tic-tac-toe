# Tic-Tac-Toe MERN App Server

This is the server-side code for a Tic-Tac-Toe MERN (MongoDB, Express.js, React.js, Node.js) application. It handles user authentication and provides endpoints for user signup and login.

## Getting Started

To run this server locally, follow these steps:

1. Clone this repository to your local machine.
2. Install dependencies by running `npm install`.
3. Ensure you have MongoDB installed and running.
4. Update the `api_key` and `api_secret` variables in `index.js` with your Stream Chat API key and secret.
5. Start the server by running `npm start`.
6. The server will be running on `http://localhost:3001`.

## Endpoints

### Signup

- **URL:** `/signup`
- **Method:** `POST`
- **Request Body:**
  - `firstName`: First name of the user.
  - `lastName`: Last name of the user.
  - `username`: Username chosen by the user.
  - `password`: Password chosen by the user.
- **Response:**
  - `token`: Authentication token for the user.
  - `userId`: Unique identifier for the user.
  - `firstName`: First name of the user.
  - `lastName`: Last name of the user.
  - `username`: Username of the user.
  - `hashedPassword`: Hashed password stored in the database.

### Login

- **URL:** `/login`
- **Method:** `POST`
- **Request Body:**
  - `username`: Username of the user.
  - `password`: Password of the user.
- **Response:**
  - `token`: Authentication token for the user.
  - `firstName`: First name of the user.
  - `lastName`: Last name of the user.
  - `username`: Username of the user.
  - `userId`: Unique identifier for the user.

## Dependencies

- `express`: For building the RESTful API.
- `cors`: Middleware for enabling CORS (Cross-Origin Resource Sharing).
- `stream-chat`: SDK for integrating Stream Chat.
- `uuid`: For generating unique user IDs.
- `bcrypt`: For hashing passwords securely.
- `os`: For accessing operating system information.

## Notes

- Make sure to keep your Stream Chat API key and secret secure.
- Implement client-side authentication to securely store and manage user tokens.
- Always hash sensitive data like passwords before storing them in the database.

