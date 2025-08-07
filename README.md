# 👥 Co-Editor

A real-time collaborative code editor built using **React**, **Socket.io**, and **Express**.  
Co-Editor allows multiple users to join a room and collaborate on code simultaneously — similar to tools like Google Docs or VS Code Live Share.

---

## 🌟 Features

- Real-time collaborative editing
- Unique room-based sessions
- Shareable Room ID
- CodeMirror integration for a powerful code editing experience
- Toast notifications and smooth UI
- Built with React, Express, and Socket.IO

---

## 🛠️ Tech Stack

- **Frontend**: React, CodeMirror, React Router, React Hot Toast
- **Backend**: Express, Socket.IO
- **Utilities**: UUID for unique room ID generation

---

## 📦 Installation

To run **Co-Editor** locally, follow these steps:

```bash
# 1. Clone the repository
git clone https://github.com/Arpit06k/co-editor.git
cd co-editor

# 2. Install dependencies (for both frontend and backend)
npm install

# 3. Start the frontend development server
npm run start:front

# 4. In a separate terminal, start the backend server (Express + Socket.io)
npm run server:dev
