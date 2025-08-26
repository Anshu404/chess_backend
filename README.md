# Chess Backend Server

This is a WebSocket-based server designed to manage real-time communication for a multiplayer chess game. It handles game logic, player authentication, and state management using a robust tech stack.

## ✨ Features

- Real-time multiplayer gameplay using WebSockets (Socket.IO).
- JWT-based user authentication.
- Scalable session management with Redis.
- [Add any other features you know about]

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Real-time Communication:** Socket.IO
- **Language:** TypeScript
- **Database/Cache:** Redis for session handling
- **Authentication:** JSON Web Tokens (JWT), bcryptjs

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v18 or later recommended)
- [npm](https://www.npmjs.com/)
- A running [Redis](https://redis.io/docs/getting-started/installation/) instance.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Anshu404/chess_backend.git](https://github.com/Anshu404/chess_backend.git)
    cd chess_backend
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    Create a file named `.env` in the root of the project and add the necessary variables. Based on the project, you'll likely need:
    ```env
    PORT=8080
    REDIS_URL=redis://localhost:6379
    JWT_SECRET=your_super_secret_key
    ```

### Running the Application

1.  **Build the TypeScript code:**
    ```bash
    npm run build
    ```

2.  **Run in development mode (with auto-reloading):**
    ```bash
    npm run dev
    ```

3.  **Run in production mode:**
    ```bash
    npm run start
    ```

The server should now be running on the port you specified in your `.env` file.

## 🙏 Acknowledgements

- This project is based on the original work by **ME and GUIDANCE UNDER VARIOUS LLMS**.
