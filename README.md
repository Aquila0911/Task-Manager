# TASK MANAGER

This Task Manager project is a full-stack web application built with Node.js and Express for the backend, and simple HTML, CSS, and JavaScript for the frontend. It allows users to manage their tasks efficiently with functionalities to create, read, update, and delete (CRUD) tasks stored in a MongoDB Atlas database.

## Features

- **CRUD Operations**: Users can create, read, update, and delete tasks.
- **Frontend**: Simple interface built with HTML, CSS, and JavaScript.
- **Backend**: Built with Node.js and Express.
- **Database**: Tasks are stored in MongoDB Atlas, ensuring data persistence and scalability.
- **Middleware**: Custom middleware for handling 404 Not Found errors and other custom errors efficiently.

## Getting Started

### Prerequisites

- Node.js installed.
- A MongoDB Atlas account and a cluster set up.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aquila0911/Task-Manager.git
   ```

2. Navigate to project directory:
   ```bash
   cd task-manager
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add MongoDB Atlas URI:
   ```env
   MONGO_URI=[your uri]
   ```

5. Start the server
   ```bash
   npm start / npm run dev (nodemon)
   ```

---
