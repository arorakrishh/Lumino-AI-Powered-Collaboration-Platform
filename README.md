# Lumino: AI-Powered Collaboration Platform
Lumino is a real-time collaboration system that goes beyond basic chat. It integrates messaging, file sharing, task management, and AI-powered meeting insights into one unified application. Built with React, Node.js/Express, Socket.IO, and modern databases, it delivers a scalable and production-ready collaboration experience.



## Table of Contents
1.  [Features](#features)
2.  [Tech Stack](#tech-stack)
3.  [Project Structure](#project-structure)
4.  [Getting Started](#getting-started)
*   [Prerequisites](#prerequisites)
*   [Installation](#installation)
*   [Running the Application](#running-the-application)
5.  [Testing the Application](#testing-the-application)
6.  [Future Enhancements](#future-enhancements)
7.  [Author](#author)



## 🚀 Features
*   **Real-Time Messaging:** Bi-directional chat powered by Socket.IO with room-based conversations.
*   **Task Management:** Create, assign, and track tasks directly within chat rooms.
*   **File Sharing:** Upload and share documents, images, and resources seamlessly.
*   **AI Summarization:** Leverages OpenAI/Gemini APIs to capture meeting highlights and generate actionable insights.
*   **User Authentication:** Secure login and session management.
*   **Scalable Architecture:** Modular frontend (React) and backend (Node.js/Express) with support for PostgreSQL/MongoDB.



## 🛠️ Tech Stack
*   **Frontend:** React, Context API, Tailwind CSS
*   **Backend:** Node.js, Express, Socket.IO
*   **Database:** PostgreSQL & MongoDB (hybrid usage for structured/unstructured data)
*   **AI Integration:** OpenAI / Gemini API for intelligent summarization
*   **Other Tools:** Docker, JWT Authentication, Concurrently



## 📂 Project Structure
```
Lumino/
├── server.js         # Main backend server with Express & Socket.IO
├── /client           # React frontend
│   ├── /src
│   │   ├── components  # UI Components (Chat, Tasks, Files)
│   │   ├── context     # State Management
│   │   ├── pages       # Views (Login, Dashboard, Collaboration Room)
│   │   └── utils       # Helpers (API calls, formatters)
├── /models           # Database Schemas (User, Task, File, Message)
├── /routes           # REST API Routes
├── /services         # AI Summarization & File Handling
└── package.json
```



## ⚡ Getting Started
This section guides you through setting up and running the Lumino collaboration platform on your local machine.



### Prerequisites
Ensure you have the following installed:

*   Node.js (v14+ recommended)
*   npm / yarn
*   Git
*   PostgreSQL + MongoDB



### Installation
1.  **Clone the repository:**

Clone the repository to your local machine using the following commands:

```bash
git clone https://github.com/arorakrishh/realtime-chat-app.git
cd realtime-chat-app
```

2.  **Install dependencies:**

Install server dependencies:

```bash
npm install
```

Install client dependencies:

```bash
cd client
npm install
cd ..
```



### Running the Application
You can run the application using the following npm scripts:

*   **Run server only:**

```bash
npm run server
```

This command starts the backend server using `nodemon`, which automatically restarts the server upon detecting code changes.

*   **Run client only:**

```bash
npm run client
```

This command starts the React frontend application.

*   **Run both concurrently:**

```bash
npm run dev
```

This command starts both the backend server and the React frontend application simultaneously using `concurrently`.



## Testing the Application
To test the application with multiple users, open the application in different browsers or use incognito mode. Then, join the same chat room and verify that messages are sent and received in real-time between the different users.



## 🔮 Future Enhancements
*   Video/Audio conferencing integration
*   Role-based access control
*   Advanced analytics dashboard for collaboration patterns
*   Mobile-friendly UI



## 👨‍💻 Author
Krish Arora

*   LinkedIn: [Krish Arora](https://www.linkedin.com/in/krish-arora-)
