# ✨ NoteSpace – Notes Management System

A full-stack Notes Management System designed to help users create, organize, manage and explore their notes through a clean and user-friendly interface.

## 📌 Project Overview

NoteSpace is a web-based application that provides users with a personal workspace to manage their ideas and information. Users can securely register, log in, create notes, organize them by visibility and manage their saved content.

The application uses React for the frontend, Node.js and Express.js for backend services, and MongoDB for database management.

## 🚀 Features

- **User Authentication:** Secure user registration and login using JWT authentication.
- **Create Notes:** Create notes with titles and descriptions.
- **Edit Notes:** Update existing notes whenever required.
- **Private Notes:** Keep personal notes accessible only to their owners.
- **Public Notes:** Share notes publicly with other users.
- **Favorites:** Mark important notes as favorites.
- **Archive Notes:** Move notes to the archived section.
- **Trash Management:** Move notes to Trash, restore them or permanently delete them.
- **Search Functionality:** Search notes easily.
- **Dashboard:** View personal workspace statistics and recent notes.
- **Profile Management:** View account information and note statistics.
- **Responsive Design:** Interface adapted for desktop and mobile screens.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JSON Web Token (JWT), bcryptjs |
| API Communication | Fetch API |
| Development Tools | Visual Studio Code, Git, GitHub |

## 📂 Project Structure

```text
NoteSpace/
│
├── config/
│   └── db.js
│
├── controllers/
│   ├── authController.js
│   └── noteController.js
│
├── middleware/
│   └── authMiddleware.js
│
├── models/
│   ├── Note.js
│   └── User.js
│
├── routes/
│   ├── authRoutes.js
│   └── noteRoutes.js
│
├── src/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── server.js
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Nishtha270906/NoteSpace.git
```

### 2. Navigate to the Project Folder

```bash
cd NoteSpace
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

Use your own MongoDB connection string and a strong private JWT secret.

**Important:** Never upload your `.env` file or expose your database credentials.

### 5. Start the Backend Server

```bash
node server.js
```

The backend server runs on:

`http://localhost:5000`

### 6. Start the Frontend

Open a second terminal and run:

```bash
npm run dev
```

Open the local Vite URL displayed in the terminal.

## 🔐 Authentication and Security

- JWT-based authentication.
- Password hashing using bcryptjs.
- Protected note management routes.
- Environment variables for sensitive configuration.
- User-specific note ownership checks.

## 🎯 Project Objective

The objective of NoteSpace is to develop a practical full-stack web application that demonstrates frontend development, backend API integration, database connectivity, authentication, CRUD operations and responsive user interface design.

## 👩‍💻 Developed By

**Nishtha**

B.Tech – Computer Science and Engineering

## 🔗 GitHub Repository

[NoteSpace – GitHub](https://github.com/Nishtha270906/NoteSpace)

---

*NoteSpace – Your thoughts. Your space. Your productivity.* ✨