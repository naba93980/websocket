## WebSocket

A collection of Node.js projects exploring real-time, bidirectional communication using Socket.IO and native WebSockets, with integrations involving React, Redis, and server-rendered EJS views.

### Overview

This repository contains three independent projects demonstrating different approaches to implementing real-time communication in Node.js applications.

The projects cover Socket.IO-based communication with a React frontend, a Redis-integrated Socket.IO chat application using EJS for dynamic server-rendered views, and native WebSocket communication using the `ws` library.

### Topics Covered

- **Communication Model:** Real-time, bidirectional client-server communication
- **WebSocket Fundamentals:** WebSocket connections and event-driven communication
- **Socket.IO:** Integration with React, Node.js, Redis
- **Server-Side Rendering:** Dynamic views using EJS templates
- **Native WebSockets:** Client-server implementation using the `ws` library
- **Message Broadcasting:** Broadcasting messages to connected WebSocket clients


**Project descriptions:**

1. **socket_io:** A real-time communication project using Socket.IO, with a React-based frontend and Node.js backend.
2. **socketio-redis-chat:** A Node.js chat application integrating Socket.IO and Redis, with EJS templates for dynamically rendered views.
3. **websocket_codedamn:** A native WebSocket implementation using the `ws` library, demonstrating client-server communication and message broadcasting.

### Getting Started

**Prerequisites:** Node.js, npm, and Redis (for the Redis-integrated project)

Each project is independent and has its own dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/naba93980/websocket.git
   ```

2. Navigate to the project you want to run.

   **Socket.IO + React:**

   ```bash
   cd websocket/socket_io/backend
   npm install
   ```

   Install frontend dependencies separately:

   ```bash
   cd ../frontend/chatty
   npm install
   ```

   **Socket.IO + Redis + EJS:**

   ```bash
   cd websocket/socketio-redis-chat
   npm install
   ```

   **Native WebSocket (`ws`):**

   ```bash
   cd websocket/websocket_codedamn/server
   npm install
   ```

3. Start the required services, including Redis for the Redis-integrated project at port 6379

4. Run the respective backend and frontend applications using the scripts or entry points defined in their individual `package.json` files.
    ```bash
   npm start
   ```

### Purpose

A collection of hands-on implementations for understanding WebSocket-based communication, exploring Socket.IO abstractions, integrating Redis into real-time applications, and working directly with the native WebSocket protocol using Node.js.