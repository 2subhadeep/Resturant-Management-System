<<<<<<< HEAD
# POS Restaurant System

This repository contains a full-stack Point of Sale (POS) system for restaurants, featuring a Node.js/Express backend and a modern React frontend. The system is designed to manage orders, tables, payments, and users efficiently, providing a seamless experience for both restaurant staff and customers.

## Project Structure

```
POS-restraunt/
  POS-Backend/      # Node.js/Express backend
  POS-Frontend/     # React frontend (Vite)
```

---

## POS-Backend

- **Location:** `POS-Backend/`
- **Tech Stack:** Node.js, Express, Sequelize (ORM), JWT, etc.
- **Features:**
  - User authentication and management
  - Table management
  - Order processing
  - Payment handling
  - Centralized error handling
- **Key Folders:**
  - `controllers/` — Business logic for each resource
  - `models/` — Sequelize models for database tables
  - `routes/` — API endpoints
  - `middlewares/` — Error handling, token verification
  - `config/` — Database and app configuration

### Getting Started (Backend)

1. Navigate to the backend folder:
   ```sh
   cd POS-Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure your database in `config/database.js` and other settings in `config/config.js`.
4. Start the backend server:
   ```sh
   npm start
   ```

---

## POS-Frontend

- **Location:** `POS-Frontend/`
- **Tech Stack:** React, Vite, Redux Toolkit, Axios, CSS
- **Features:**
  - User login/register
  - Dashboard with metrics
  - Menu browsing and order placement
  - Table and order management
  - Invoice generation
- **Key Folders:**
  - `src/components/` — UI components (auth, dashboard, menu, tables, etc.)
  - `src/pages/` — Main pages (Home, Dashboard, Orders, etc.)
  - `src/redux/` — State management
  - `src/https/` — Axios wrappers for API calls
  - `src/assets/` — Images and static assets

### Getting Started (Frontend)

1. Navigate to the frontend folder:
   ```sh
   cd POS-Frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. The app will be available at `http://localhost:5173` by default.

---

## Environment Variables

- **Backend:** Configure database and JWT secrets in `config/config.js` and `config/database.js`.
- **Frontend:** Update API base URLs in `src/https/index.js` as needed.

---

## Screenshots

Add screenshots of the application in the `POS-Frontend/src/assets/images/` folder and reference them here for documentation.

---

## License

This project is for educational and demonstration purposes. Please review and update the license as needed for your use case.

---

## Author

- Your Name
- [Your Contact/Portfolio]
=======
# Resturant-Management-System
>>>>>>> 838b5018f69a30b59afe14785736373a4b62c338
