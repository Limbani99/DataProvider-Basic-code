# 🔐 React Data Provider Authentication Context

A reusable React Context API setup for handling authentication, user state management, token persistence, and protected API requests using Axios interceptors.

This project demonstrates how to create a centralized authentication system in React using Context API and Hooks for scalable frontend applications.

---

# 🚀 Features

- User Authentication Management
- Global State Management using Context API
- Login & Logout Functionality
- Token Storage using LocalStorage & SessionStorage
- Persistent Authentication after Refresh
- Axios Request Interceptor
- Automatic Authorization Header Injection
- Custom React Hook (`useData`)
- Role-Based State Handling

---

# 🛠 Tech Stack

- React.js
- Context API
- React Hooks
- Axios
- JavaScript (ES6)

---

# 📂 Project Structure

```bash
src/
│
├── context/
│   └── DataProvider.jsx
│
└── App.jsx
```

---

# 📜 Code Overview

## Authentication Context

The `DataProvider` component provides:

- Global User State
- Authentication Token Management
- Login & Logout Functions
- Axios Authorization Interceptor
- Persistent Session Handling

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Limbani99/DataProvider-Basic-code.git
```

---

## Install Dependencies

```bash
npm install
```

---

## Start Development Server

```bash
npm run dev
```

---

# 💡 Usage Example

## Wrap App with Provider

```jsx
import { DataProvider } from "./context/DataProvider";

<DataProvider>
    <App />
</DataProvider>
```

---

## Access Context Data

```jsx
import { useData } from "./context/DataProvider";

const { user, login, logout } = useData();
```

---

# 🔐 Functionalities Included

- Save user data in LocalStorage
- Save JWT token securely
- Restore session after refresh
- Inject token automatically in API requests
- Clear authentication data on logout

---

# 🌟 Why This Project?

This setup helps developers create scalable and maintainable authentication systems in React applications without prop drilling.

It is useful for:
- MERN Stack Projects
- Admin Dashboards
- E-Commerce Websites
- Authentication Systems
- Role-Based Applications
---

# ⭐ Support

If you found this helpful, give this repository a ⭐ on GitHub.
