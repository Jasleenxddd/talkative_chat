# Talkative — Real-Time Chat Application

Talkative is a full-stack messaging application built using the MERN stack. It brings together a React frontend and a Node.js backend, with Socket.IO enabling real-time communication between connected users.

**Tech Stack:** React.js · Node.js · Express.js · MongoDB · Socket.IO

**Repository:** [Jasleenxddd/talkative_chat](https://github.com/Jasleenxddd/talkative_chat)

## Features

- **Real-Time Messaging:** Exchange messages using Socket.IO for bidirectional communication.
- **Full-Stack Architecture:** Separate frontend and backend applications within a single repository.
- **REST APIs:** Backend endpoints built with Node.js and Express.js.
- **Database Integration:** MongoDB for persistent application data.
- **Responsive User Interface:** React.js-based interface for interacting with the application.

> Include authentication, online status, private chats, typing indicators, or message history in this list only if those features are implemented in your code.

## Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js, JavaScript, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Real-Time Communication | Socket.IO |
| Version Control | Git, GitHub |

## Project Structure

```text
talkative_chat/
├── frontend/       # React frontend
├── backend/        # Express and Node.js backend
├── .gitignore
└── README.md
```

Additional root-level configuration files may be present depending on your setup.

## Getting Started

### Prerequisites

Install the following before running the application:

- [Node.js](https://nodejs.org/)
- npm, included with Node.js
- [MongoDB](https://www.mongodb.com/) or a MongoDB Atlas connection
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Jasleenxddd/talkative_chat.git
cd talkative_chat
```

### 2. Configure the backend

```bash
cd backend
npm install
```

Create a `.env` file in the backend directory using the variable names expected by your backend code. A typical configuration may look like this:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

Add any additional variables required by your implementation, such as authentication secrets or frontend origins. Use the exact names referenced in your source code.

Start the backend using the script defined in `backend/package.json`. For example:

```bash
npm run dev
```

If your project uses a different script, run the appropriate command from that package's `scripts` section.

### 3. Configure the frontend

Open a second terminal:

```bash
cd frontend
npm install
```

Configure the backend API URL using the environment variable convention supported by your frontend build tool, if required.

Start the frontend using the script defined in `frontend/package.json`. For a typical React project:

```bash
npm run dev
```

For projects using Create React App, the development command may instead be:

```bash
npm start
```

### 4. Run the application

Ensure the backend and frontend are both running. Open the local URL printed by the frontend development server in your browser.

Confirm that your MongoDB connection is working and that the frontend is configured to connect to the correct backend URL.

## How It Works

1. The user interacts with the React frontend.
2. The frontend communicates with the Express backend for supported API operations.
3. MongoDB stores application data.
4. Socket.IO enables real-time, bidirectional communication between connected clients.

The exact event flow and persistence behavior depend on the implementation in the repository.

## Engineering Highlights

- Organized a full-stack application into frontend and backend components.
- Integrated real-time communication into a web application.
- Connected client-side functionality with backend APIs and database operations.
- Consolidated the application into a single repository for easier development and maintenance.

## Future Improvements

Potential extensions include:

- Private conversations and group chats
- Online presence and typing indicators
- Message delivery and read receipts
- Message search and pagination
- Automated tests and CI/CD
- Production deployment with environment-specific configuration

## Author

**Jasleen Kaur**

- GitHub: [@Jasleenxddd](https://github.com/Jasleenxddd)
- Project: [Talkative](https://github.com/Jasleenxddd/talkative_chat)

---

*Built as a full-stack web development project to explore real-time communication, API integration, and MERN-stack application development.*
