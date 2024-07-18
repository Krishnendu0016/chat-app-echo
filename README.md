

# Chat Application Echo

This is a full-stack chat application using React for the frontend and Express for the backend. It utilizes Chakra UI for styling and React Router for navigation. The app supports routing between a homepage and a chat page and uses a custom context provider for managing chat state. The backend uses MongoDB for database operations and Socket.IO for real-time communication.


## Features
- **Chakra UI Integration**: Provides a consistent and responsive UI.
- **React Router**: Enables navigation between the homepage and chat page.
- **Chat Context**: Manages chat state throughout the application.
- **Real-time Communication**: Uses Socket.IO for real-time messaging.
- **Secure Authentication**: Implements JWT for secure authentication.

## Tech Stack
### Frontend
- **React**: JavaScript library for building user interfaces.
- **Chakra UI**: A simple, modular, and accessible component library.
- **React Router**: Declarative routing for React applications.

### Backend
- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing chat data.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **Socket.IO**: Enables real-time bidirectional event-based communication.
- **JWT**: Secure token-based authentication.

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

```

- **backend/**: Contains the backend server code.
  - **config/**: Configuration files (e.g., database connection).
  - **controllers/**: Functions to handle requests.
  - **models/**: Mongoose schemas and models.
  - **routes/**: Express route definitions.
  - **server.js**: Entry point for the backend server.
  - **.env**: Environment variables file.
- **frontend/**: Contains the frontend source code.
  - **public/**: Contains the HTML file and other static assets.
  - **src/**: Contains the source code for the application.
    - **Components/**: Directory for reusable components.
    - **Context/**: Contains the ChatProvider context.
    - **Pages/**: Contains the page components (Homepage and Chatpage).
    - **App.js**: Main application component.
    - **index.js**: Entry point of the application.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

---
