### ============================================
## 🍪 Cookie Authentication System (Client Side)
### ============================================

## 📌 PROJECT OVERVIEW
This is a simple but powerful authentication system built using
Node.js, Express, and EJS. It demonstrates how cookie-based
authentication works in real web applications.

Users can log in, access a protected dashboard, and log out using
secure cookie handling.

### --------------------------------------------
## ⚡ FEATURES
### --------------------------------------------

- ✔ User Login System (Static Users)
- ✔ Cookie-Based Authentication 🍪
- ✔ Protected Dashboard Route
- ✔ Session Persistence using Cookies
- ✔ Logout Functionality
- ✔ Route Protection (Middleware-like logic)

### --------------------------------------------
## 🛠️ TECH STACK
### --------------------------------------------

- Node.js
- Express.js
- EJS (Template Engine)
- cookie-parser
- HTML/CSS (Bootstrap optional)

### --------------------------------------------
## 🔐 AUTHENTICATION FLOW
### --------------------------------------------

-  User enters credentials (login page)
- Server verifies user from memory database
- If valid:
  - → Cookie is created (userData) 🍪
  - → Stored in browser automatically
- On next requests:
  - → Cookie is sent automatically
  - → Server validates user session
- Logout clears the cookie

### --------------------------------------------
## 📁 PROJECT STRUCTURE
### --------------------------------------------
```
cookie-auth-client-ejs/
│
├── views/
│ ├── home.ejs
│ ├── login.ejs
│ └── dashboard.ejs
│
├── server.js
├── package.json
└── README.md


### --------------------------------------------
## 🌐 ROUTES
### --------------------------------------------

- GET  /            → Home page
- GET  /login       → Login page
- POST /login       → Authenticate user
- GET  /dashboard   → Protected dashboard
- GET  /logout      → Clear cookie & logout


### --------------------------------------------
## 👤 SAMPLE USERS
### --------------------------------------------

```bash id="pro2"
username: john
password: 123
role: admin

username: Sarah
password: 456
role: user
```
###  --------------------------------------------
## 🧠 LEARNING OUTCOMES
### --------------------------------------------

- How cookies work in web applications
- How authentication flow works in Express
- How to protect routes using cookies
- How session-like behavior is created
- Frontend + backend integration using EJS

### --------------------------------------------
## 🚀 HOW TO RUN PROJECT
### --------------------------------------------
### 1. Install dependencies
```
npm install
```
### 2. Start server
```
node server.js
```
### OR (if nodemon installed)
```
npm run server
```
### 3. Open browser
```
http://localhost:3000
```
--------------------------------------------
### 📌 FUTURE IMPROVEMENTS
--------------------------------------------

- Add MongoDB database integration
- Replace cookies with JWT authentication
- Add password hashing (bcrypt)
- Add user registration system
- Add role-based access control (admin/user)

--------------------------------------------
### 👨‍💻 AUTHOR
--------------------------------------------

Created by: Ifra Malik
Purpose: Learning Authentication Concepts (Node.js)

============================================
⭐ If you like this project, give it a star!
============================================
