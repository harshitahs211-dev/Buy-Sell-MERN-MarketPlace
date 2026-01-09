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
```

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

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

---

### Installation

1.Clone the repository
```bash
git clone <your-repo-url>
cd "buy sell"
```

### Development Tools
- Nodemon
- Concurrently

---

2.Install backend dependencies
```
cd backend
npm install
```

3.Environment Setup Create .env file in backend directory:
Create a .env file inside backend/:
```
MONGODB_URI=mongodb://localhost:27017/buysell
JWT_SECRET=your_jwt_secret_key
PORT=8080
```

4.Start backend:
```
npm run dev
```

5.Frontend Setup
```
cd ../frontend
npm install
npm start
```

📧 API Endpoints


📧 API Endpoints

Authentication



1.POST /api/users/register - User registration

2.POST /api/users/login - User login

Products


1.GET /api/products/shop - Get all products

2.POST /api/products/add - Add new product

3.PUT /api/products/:id - Update product

4.DELETE /api/products/:id - Delete product



Cart & Orders


1.POST /api/products/addtocart - Add to cart

2.GET /api/products/cart - Get cart items

3.POST /api/orders/buynow - Place order

4.GET /api/orders/myorders - Get user orders

🤝 Contributing

1.Fork the repository

2.Create your feature branch

3Commit your changes

4.Push to the branch

5.Open a pull request

👨‍💻 Author

Harshita Sharma - Full Stack Developer

Built with ❤️ using the MERN stack
