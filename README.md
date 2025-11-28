# Chatbot Frontend

A **React.js + Vite + TailwindCSS** frontend for the Chatbot application, providing a responsive UI for user authentication, chat management, and conversation display. It consumes the backend API for all chat and user-related operations.

---

## Table of Contents

* [Features](#features)
* [Folder Structure](#folder-structure)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Environment Variables](#environment-variables)
* [Available Pages](#available-pages)
* [Components](#components)
* [Contexts](#contexts)
* [Running the Frontend](#running-the-frontend)
* [Contributing](#contributing)
* [License](#license)

---

## Features

* User login and verification
* Responsive chat interface
* Sidebar with conversation list
* Loading states for API requests
* Real-time updates using Context API

---

## Folder Structure

```
frontend/
├── .env
├── .eslintrc.cjs
├── .gitignore
├── README.md
├── index.html
├── node_modules/ (ignored)
├── package-lock.json
├── package.json
├── postcss.config.js
├── public/
│   └── vite.svg
├── src/
│   ├── App.jsx
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Loading.jsx
│   │   └── Sidebar.jsx
│   ├── context/
│   │   ├── ChatContext.jsx
│   │   └── UserContext.jsx
│   ├── index.css
│   ├── main.jsx
│   └── pages/
│       ├── Home.jsx
│       ├── Login.jsx
│       └── Verify.jsx
├── tailwind.config.js
└── vite.config.js
```

---

## Technologies Used

* React.js
* Vite (build tool)
* TailwindCSS for styling
* Context API for state management
* Fetch API for HTTP requests
* ESLint for code quality

---

## Installation

1. Clone the repository:

```bash
git clone <your-frontend-repo-url>
cd frontend
```

2. Install dependencies:

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory with any required variables. For example:

```env
VITE_BACKEND_URL=http://localhost:5000
```

> **Note:** `.env` is ignored in `.gitignore` to keep secrets safe.

---

## Available Pages

* **Home.jsx**: Main chat interface
* **Login.jsx**: User login page
* **Verify.jsx**: Verification page for login/signup

---

## Components

* **Header.jsx**: Top navigation bar
* **Sidebar.jsx**: Displays conversations
* **Loading.jsx**: Loading spinner for async operations

---

## Contexts

* **UserContext.jsx**: Provides user authentication state across the app
* **ChatContext.jsx**: Provides chat messages and conversation state

---

## Running the Frontend

Start the development server:

```bash
npm run dev
```

Your app will be available at `http://localhost:5173` (default Vite port).

---

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

---

## License


© 2025 mky120799@gmail.com
