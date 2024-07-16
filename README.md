# PRODIGY_FSWD_01
# Secure User Authentication System

This project is a secure user authentication system built with Node.js, Express.js, and MongoDB. 
It includes functionality for user registration, login, session management, and role-based access control (RBAC).

# Tech Stack

- Backend: Node.js with Express.js
- Database: MongoDB
- Authentication: Passport.js
- Password Hashing: bcrypt.js
- Session Management: express-session



## Project Structure

```plaintext
project-root/
│
├── controllers/
│   ├── authController.js
│   └── userController.js
│
├── models/
│   └── User.js
│
├── routes/
│   ├── authRoutes.js
│   └── protectedRoutes.js
│
├── middlewares/
│   └── authMiddleware.js
│
├── config/
│   └── passportConfig.js
│
├── views/
│   └── error.ejs
│
├── .env
├── server.js
├── package.json
└── README.md

