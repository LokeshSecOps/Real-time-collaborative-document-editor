# Real-time-collaborative-document-editor

A full-stack web application that allows multiple users to edit documents simultaneously in real time.

This project, developed as Task 3 for the CodTech IT Solutions internship, is a full-stack Real-Time Collaborative Document Editor designed to enable seamless multi-user editing of rich text documents. The goal was to build a dynamic, responsive, and scalable application that allows multiple users to edit the same document simultaneously, with changes reflected in real time across all connected clients.

The frontend is built using React.js and Vite, offering a fast development experience and modular architecture. For the rich text editing interface, Quill.js was integrated to provide formatting tools and intuitive user interaction. Real-time communication is powered by Socket.IO, enabling instant broadcasting of text changes between users.

The backend is implemented using Node.js and Express, with Socket.IO handling WebSocket connections. This setup ensures low-latency updates and efficient data flow. The server listens for text changes and emits updates to all other connected clients, maintaining document consistency across sessions.

---

## 🚀 Features

- 🔄 Real-time collaborative editing
- 🖋️ Rich text editor using Quill.js
- 🧠 Socket.IO for live sync across clients 

