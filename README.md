# FlashGrocer 🛒⚡

FlashGrocer is a full-featured Quick-Commerce (Q-Commerce) grocery delivery platform with a responsive frontend, Node.js & Express REST API backend, SQLite database, and JWT authentication.

---

## 🚀 Features

- **Storefront & Catalog**: Browse categories (Food, Grocery, Electronics, Clothes, Daily Essentials), product cards, search, and filter.
- **Shopping Cart & Checkout**: Real-time cart calculation, quantity adjustments, and smooth checkout flow.
- **User Authentication**: Secure user registration, login, JWT token auth, and role-based access (Customers & Admins).
- **Admin Dashboard**: Manage inventory, products, orders, and view sales stats.
- **Wishlist & Deals**: Flash sales, discounted deals, and wishlist saving.
- **RESTful API**: Clean API architecture with structured routes, controllers, and middleware.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla ES6+), FontAwesome
- **Backend**: Node.js, Express.js
- **Database**: SQLite (via `better-sqlite3` / `mongoose`)
- **Security**: JWT (`jsonwebtoken`), bcryptjs, Helmet, Express Rate Limit, Express Validator

---

## 📦 Getting Started

### 1. Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed (v16 or higher).

### 2. Install Dependencies
```bash
npm install
```

### 3. Initialize Database & Seed Data
```bash
npm run seed:admin
```

### 4. Start the Application
Run in development mode:
```bash
npm run dev
```

Or start standard production server:
```bash
npm start
```

Open your browser and navigate to:
```
http://localhost:3000
```

---

## 📁 Project Structure

```text
├── 01_API_Files/           # API documentation, testing, and Postman collections
├── database/               # Database setup, schema, and seed scripts
├── images/                 # Product and UI images
├── middleware/             # Auth, validation, and error-handling middleware
├── routes/                 # REST API route handlers (auth, products, cart, orders, admin)
├── index.html              # Main storefront page
├── login.html              # User login and registration page
├── sale.html               # Deals and flash sale page
├── styles.css              # Main styles and UI styling
├── script.js               # Frontend application logic
├── server.js               # Express server entry point
├── package.json            # Project dependencies and npm scripts
└── README.md               # Project documentation
```

---

## 📄 License
This project is licensed under the ISC License.
