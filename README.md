# Real-Time Chat Application

A modern, real-time chat application built with React and Node.js, featuring real-time messaging using Socket.IO.

## Project Structure

The project is divided into two main components:

- `client/`: Frontend application built with React
- `server/`: Backend server built with Node.js and Express

## Features

- Real-time messaging using Socket.IO
- User authentication and management
- Emoji support in messages
- Responsive design
- Modern UI with React components
- Scroll-to-bottom functionality for chat messages

## Tech Stack

### Frontend (Client)
- React 16.9.0
- React Router DOM
- Socket.IO Client
- React Emoji
- React Scroll to Bottom

### Backend (Server)
- Node.js
- Express.js
- Socket.IO
- CORS

## Getting Started

### Prerequisites
- Node.js (v12 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install client dependencies:
   ```bash
   cd client
   npm install
   ```
3. Install server dependencies:
   ```bash
   cd server
   npm install
   ```

### Running the Application

1. Start the server:
   ```bash
   cd server
   npm start
   ```

2. In a new terminal, start the client:
   ```bash
   cd client
   npm start
   ```

The application will be available at `http://localhost:3000`

## Project Organization

```
project_chat_application/
├── client/           # Frontend React application
│   ├── public/      # Static files
│   └── src/         # React source code
├── server/          # Backend Node.js server
│   ├── index.js     # Main server file
│   ├── router.js    # API routes
│   └── users.js     # User management
└── .github/         # GitHub Actions configuration
```

## Acknowledgments

- Socket.IO for real-time communication
- React community for excellent documentation and support
- All contributors who have helped improve this project
