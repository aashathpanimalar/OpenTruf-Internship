
# 🌶️ Pepper Paradise – E-commerce Website

**Pepper Paradise** is a full-stack e-commerce platform focused exclusively on **chillies and pepper-based products**. Developed during my 6-month internship at **Opentruf Technologies**, this project showcases a complete real-world application built with modern web technologies.

---

## 📁 Repository Structure

```

├── .gitignore
├── README.md
├── backend
│   ├── .env                  # Environment variables (not committed)
│   ├── config
│   │   └── config.js         # Database and app configuration
│   ├── controllers
│   │   └── userController.js # API logic handlers
│   ├── index.js              # Backend server entry point
│   ├── middleware
│   │   └── errorHandler.js   # Custom error handling middleware
│   ├── models
│   │   ├── index.js          # Model associations and setup
│   │   ├── order.js          # Order model
│   │   └── user.js           # User model
│   ├── package.json
│   ├── package-lock.json
│   └── routes
│       └── userRoutes.js     # API route definitions
└── frontend
├── .gitignore
├── README.md
├── package.json
├── package-lock.json
├── public
│   ├── index.html        # React root HTML
│   └── robots.txt
└── src
├── App.js            # Main React component
├── App.css
├── components        # Reusable React components
│   ├── Address.js
│   ├── Cart.js
│   ├── Category.js
│   ├── Footer.js
│   ├── ForgotPassword.js
│   ├── Login.js
│   ├── Navbar.js
│   ├── OtpComponent.js
│   ├── Payment.js
│   ├── PrivateRoute.js
│   ├── ProductCard.js
│   ├── Products.js
│   ├── address.css
│   ├── login.css
│   └── payment.css
├── index.js          # React entry point
├── index.css
├── reportWebVitals.js
└── setupTests.js

````

---

## 🔷 Project Overview

### Frontend - ReactJS  
The frontend app (inside `/frontend`) is built with ReactJS to create a smooth and dynamic user experience. Key components include:

- **Login.js & ForgotPassword.js** – User authentication and password reset flows.
- **Products.js & ProductCard.js** – Displaying product listings and details.
- **Cart.js & Payment.js** – Cart management and order checkout.
- **Navbar.js & Footer.js** – Navigation and footer components.
- **OtpComponent.js** – For OTP verification during signup/login flows.
- **PrivateRoute.js** – Protects routes for authenticated users only.

CSS files in the components folder (`login.css`, `address.css`, `payment.css`) style respective parts of the UI.

---

### Backend - NodeJS & ExpressJS  
The backend code (inside `/backend`) manages API endpoints, business logic, and database interaction:

- `index.js`: Starts the Express server and connects middleware.
- `/controllers/userController.js`: Contains logic for user authentication, product handling, and orders.
- `/routes/userRoutes.js`: Defines API routes related to user and order actions.
- `/models/`: Sequelize models for Users, Orders, and their relationships.
- `/middleware/errorHandler.js`: Custom error handling logic.
- `/config/config.js`: Database and environment configurations.

---

## 🔐 Security & Authentication

- Used **JWT (JSON Web Token)** to secure user sessions and protect APIs.
- Passwords are securely handled with hashing (bcrypt).
- Protected routes via middleware in backend and React private routes.

---

## 🗄️ Database

- **PostgreSQL** is used as the relational database.
- Models and queries are managed via **Sequelize ORM** for cleaner code and easier maintenance.

---

## 🔄 Version Control

- Git is used for version control.
- Regular commits and branches were used to manage features and bug fixes.
- The entire project is hosted on GitHub.

---

## 📝 How to Run the Project

### Backend

1. Navigate to the `backend` folder:  
   ```bash
   cd backend
````

2. Install dependencies:

   ```bash
   npm install
   ```
3. Create a `.env` file with your environment variables (database URL, JWT secret, etc.).
4. Start the backend server:

   ```bash
   npm start
   ```

### Frontend

1. Navigate to the `frontend` folder:

   ```bash
   cd frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the React development server:

   ```bash
   npm start
   ```

---

## ✨ Summary

This project gave me practical experience with:

* Building scalable frontend applications using ReactJS
* Creating REST APIs with NodeJS and ExpressJS
* Handling relational databases using PostgreSQL and Sequelize
* Implementing secure authentication using JWT
* Managing code and collaboration via Git and GitHub

---

## 📬 Contact

Feel free to reach out for any questions or suggestions!

[LinkedIn]([#](https://www.linkedin.com/in/mohamed-aashath-98ba30275)) | [GitHub Profile](https://github.com/aashathpanimalar)

---

