

# Chat Application Echo

This project is a full-fledged chat application built using the MERN stack (MongoDB, Express.js, React, Node.js). It includes one-on-one and group messaging features, real-time communication with Socket.IO, and user authentication with JWT. The application allows users to send and receive messages, manage their profiles, and receive notifications.

## Features
- **One-on-One Messaging**: Users can engage in private chats.
- **Group Chat Functionality**: Users can create and manage group chats.
- **Real-Time Messaging**: Messages are delivered instantly using Socket.IO.
- **User Profiles**: Each user can customize their profile with pictures and information.
- **Notifications**: Real-time notifications alert users of new messages.
- **User Authentication**: Secure user registration and login with encrypted passwords.
- **Persistent Data Storage**: All messages and chat history are stored in MongoDB.



## Key Technologies

- **Frontend**: React, Chakra UI
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT, Bcrypt.js, Socket.IO
- **Real-Time Messaging**: Socket.IO for instant message delivery.
- **Authentication**: User registration and login are secured using JSON Web Tokens (JWT) and password encryption with Bcrypt.
- **Database**: MongoDB for message and user data storage.


### Utilities
- **dotenv**: Loads environment variables from a .env file.
- **bcryptjs**: Password hashing.
- **nodemon**: Utility that monitors for changes in source and automatically restarts the server.

## Getting Started

### Prerequisites
- **Node.js**: Ensure you have Node.js installed. You can download it from [here](https://nodejs.org/).
- **npm**: Node package manager, which comes with Node.js.
- **MongoDB**: Ensure you have MongoDB installed. You can download it from [here](https://www.mongodb.com/try/download/community).

### Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/Krishnendu0016/chat-app.git
    cd chat-app
    ```

2. **Install frontend dependencies**:
    ```bash
    cd frontend
    npm install
    ```

3. **Install backend dependencies**:
    ```bash
    cd ../backend
    npm install
    ```

### Running the App
1. **Start the backend server**:
    ```bash
    cd backend
    npm run dev
    ```

2. **Start the frontend server**:
    ```bash
    cd ../frontend
    npm start
    ```

This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

