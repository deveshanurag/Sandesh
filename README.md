
# Sandesh: Real-Time Chat Application

A fully functional real-time chat application built using the MERN stack, enabling users to communicate through one-to-one and group chats. This project includes features such as real-time messaging, typing indicators, notifications, authentication, and authorization.

## Features

- **Real-time Messaging**: Instant messaging with live updates using `socket.io`.
- **Typing Indicators**: Displays when a user is typing in a chat.
- **Notifications**: Notifies users of new messages in chats they are part of.
- **Authentication**: Secure user authentication using JWT.
- **Authorization**: Role-based access control for chats and messages.
- **Group Chats**: Create and manage group chats with multiple users.
- **Responsive Design**: Frontend is optimized for various devices.

## Tech Stack

### Frontend
- **React**: For building the user interface.
- **Chakra UI**: For pre-styled, responsive components.

### Backend
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for handling API routes.
- **MongoDB**: NoSQL database for storing user and chat data.
- **Socket.io**: Real-time communication between clients and server.

### Other Tools
- **JWT**: For secure user authentication.
- **Bcrypt.js**: For hashing and securing user passwords.
- **dotenv**: For environment variable management.

## Installation

### Prerequisites
- Node.js installed
- MongoDB instance running locally or on the cloud (e.g., MongoDB Atlas)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/deveshanurag/Sandesh.git
   cd Sandesh
   ```

2. Install dependencies for both backend and frontend:
   ```bash
   # In the root folder
   npm install
   cd frontend
   npm install
   ```

3. Set up the `.env` file in the root directory with the following variables:
   ```env
   PORT=5000
   MONGO_URI=<your_mongo_db_connection_string>
   JWT_SECRET=<your_jwt_secret>
   ```

4. Start the server and frontend:
   ```bash
   # Start the backend server
   npm run server

   # Start the frontend development server
   cd frontend
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Demo
Demo video:(open in incognito window)

https://drive.google.com/file/d/1HX4cJFnVlsT-ZrUB3mTh2vIc29h3fiCH/view?usp=sharing

Live Website:

https://sandesh-hw3l.onrender.com/

## Project Structure

### Backend
- **/routes**: API routes for users, chats, and messages.
- **/controllers**: Logic for handling API requests.
- **/models**: MongoDB models for users, chats, and messages.
- **/middleware**: Custom middlewares for authentication and error handling.

### Frontend
- **/components**: Reusable UI components (e.g., chat box, message list).
- **/pages**: Pages such as login, register, and chat interface.
- **/context**: Global state management using Context API.

## Usage

1. **User Registration and Login**: Users can create accounts and log in securely.
2. **One-on-One Chat**: Select a user to start a private conversation.
3. **Group Chat**: Create or join a group chat and manage group members.
4. **Real-Time Communication**: Send messages instantly with live updates.

## Future Scope

- Add features like message search, media sharing, and dark mode.
- Implement video calling
- Implement push notifications for mobile and desktop users.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.
---
