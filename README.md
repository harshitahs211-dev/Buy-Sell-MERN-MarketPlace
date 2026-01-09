# 🛒 Buy-Sell MERN Marketplace

A **full-stack e-commerce marketplace** built using the **MERN stack**, featuring a modern **glassmorphism UI**, secure authentication, and complete buyer–seller workflows.

---

## 🚀 Features

### 🔐 Authentication & User Management
- User Registration with password confirmation validation  
- Secure Login using **JWT authentication**  
- Profile Management with user information display  
- Protected Routes for secure feature access  
- Session Management with automatic token expiration  

---

### 🛍️ Product Management
- Product Listing with detailed information  
- Advanced Search by product name  
- Category Filtering with multi-select options  
- Product Details Modal with full description  
- Image Display with hover effects and scaling  
- Styled Category Tags  
- Responsive Product Grid with modern card design  

---

### 🛒 Shopping Cart
- Add to Cart with real-time updates  
- Remove items from cart  
- Quantity Tracking per product  
- Visual Cart Status (added / ordered)  
- Cart Summary with total price calculation  
- Persistent Cart across user sessions  

---

### 📦 Order Management
- Secure Order Placement  
- Buyer Order History with details  
- Real-time Order Status Tracking  
- OTP Generation for delivery verification  
- Seller Order Fulfillment System  

---

### 🚚 Delivery System
- Delivery Management for sellers  
- OTP Verification for secure delivery  
- Transaction Tracking with unique IDs  
- Real-time Delivery Status Updates  
- Buyer–Seller communication via order system  

---

### 🎨 Modern UI / UX
- Glassmorphism effects with backdrop blur  
- Gradient backgrounds  
- Smooth animations & hover effects  
- Fully responsive design (mobile-first)  
- Professional typography  
- Interactive UI feedback  
- Loading states with animated spinners  
- Elegant error handling  

---

## 🛠️ Tech Stack

### Frontend
- **React.js**
- React Router DOM
- Axios
- CSS3 (Glassmorphism, Grid, Flexbox)
- Animations & Transitions
- Responsive Design

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- Mongoose
- JWT (jsonwebtoken)
- bcrypt
- dotenv
- CORS

### Development Tools
- Nodemon
- Concurrently

## 📁 Project Structure

```text
buy sell/
├── backend/
│   ├── controllers/
│   │   ├── usercontroller.js        # User authentication logic
│   │   ├── productcontroller.js     # Product management
│   │   └── ordercontroller.js       # Order processing
│   │
│   ├── models/
│   │   ├── userModel.js             # User schema
│   │   ├── productModel.js          # Product schema
│   │   └── orderModel.js            # Order schema
│   │
│   ├── routes/
│   │   ├── userRoute.js             # Authentication routes
│   │   ├── productRoute.js          # Product routes
│   │   └── orderRoute.js            # Order routes
│   │
│   ├── middleware/
│   │   └── auth.js                  # JWT authentication middleware
│   │
│   └── server.js                   # Express server configuration
│
├── frontend/
│   └── src/
│       ├── components/
│       │   └── navbar.jsx           # Navigation component
│       │
│       ├── pages/
│       │   ├── login.jsx            # Login page
│       │   ├── signin.jsx           # Registration page
│       │   ├── shop.jsx             # Product marketplace
│       │   ├── SellItem.jsx         # Product listing form
│       │   ├── myproduct.jsx        # Seller's products
│       │   ├── cart.jsx             # Shopping cart
│       │   ├── orders.jsx           # Order history
│       │   └── delivery.jsx         # Delivery management
│       │
│       └── styles/
│           ├── login.css
│           ├── signin.css
│           ├── shop.css
│           ├── sellItem.css
│           ├── myproduct.css
│           ├── cart.css
│           ├── orders.css
│           └── navbar.css
│
└── public/

## 🎯 Key Functionalities

### 🛒 For Buyers
- Browse products with search & filters
- View product details in interactive modals
- Add items to cart
- Place secure orders
- Track order status
- Receive OTP for delivery verification

### 🧑‍💼 For Sellers
- List products with detailed information
- Edit / delete inventory
- Process orders efficiently
- Generate delivery OTP
- Track sales and order fulfillment

### 🛠️ Admin Capabilities
- User authentication management
- Product CRUD operations
- Order processing and tracking
- Secure data handling

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- CSS3 (Glassmorphism, Flexbox, Grid)
- Responsive Design

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- dotenv
- CORS

### Development Tools
- Nodemon
- Concurrently

---
