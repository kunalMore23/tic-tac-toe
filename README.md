# Tic-Tac-Toe MERN Project

This project is a Tic-Tac-Toe game built using the MERN stack (MongoDB, Express, React, Node.js). It consists of both client and server applications.

## Overview

The Tic-Tac-Toe MERN Project consists of the following components:

- **Client App**: The front-end application built with React.js that provides the user interface for playing Tic-Tac-Toe.
- **Server App**: The back-end application built with Node.js and Express.js that handles user authentication, game logic, and communication with the database.

## Installation and Setup

### Client App

1. Clone the repository:

`git clone https://github.com/kunalMore23/tic-tac-toe.git`

2. Navigate to the client directory:

`cd <repository-directory>/client`

3. Install dependencies:

`npm install`

4. Start the development server:

`npm start`

The client app will run on [http://localhost:3000](http://localhost:3000).

### Server App

1. Navigate to the server directory:

`cd <repository-directory>/server`

2. Install dependencies:

`npm install`

3. Create a `.env` file in the root directory of the server and add your Stream Chat API key and secret:

``` 
STREAM_CHAT_API_KEY=your_api_key
STREAM_CHAT_API_SECRET=your_api_secret
```
4. Start the server:

`npm start`

The server app will run on [http://localhost:3001](http://localhost:3001).

## Usage

Once both the client and server apps are running, you can access the Tic-Tac-Toe game through the client app in your web browser. Sign up or log in to start playing against other users or AI.

## Technologies Used

- React.js: A JavaScript library for building user interfaces.
- Node.js: A JavaScript runtime for building server-side applications.
- Express.js: A minimalist web framework for Node.js.
- MongoDB: A NoSQL database used for storing game data and user information.
- Stream Chat: A service used for real-time chat functionality.
- bcrypt: A library used for hashing passwords securely.
- CORS: A middleware used to enable Cross-Origin Resource Sharing.
- UUID: A library used to generate unique user IDs.