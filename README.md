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

---

## 📁 Project Structure

buy sell/

├── backend/

│ ├── controllers/

│ │ ├── usercontroller.js

│ │ ├── productcontroller.js

│ │ └── ordercontroller.js

│ ├── models/

│ │ ├── userModel.js

│ │ ├── productModel.js

│ │ └── orderModel.js
│ ├── routes/
│ │ ├── userRoute.js
│ │ ├── productRoute.js
│ │ └── orderRoute.js
│ ├── middleware/
│ │ └── auth.js
│ └── server.js
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ │ └── navbar.jsx
│ │ ├── pages/
│ │ │ ├── login.jsx
│ │ │ ├── signin.jsx
│ │ │ ├── shop.jsx
│ │ │ ├── SellItem.jsx
│ │ │ ├── myproduct.jsx
│ │ │ ├── cart.jsx
│ │ │ ├── orders.jsx
│ │ │ └── delivery.jsx
│ │ └── styles/
│ │ ├── login.css
│ │ ├── signin.css
│ │ ├── shop.css
│ │ ├── sellItem.css
│ │ ├── myproduct.css
│ │ ├── cart.css
│ │ ├── orders.css
│ │ └── navbar.css
│
└── public/


---

## 🎯 Key Functionalities

### For Buyers
- Browse products with search & filters  
- View product details in modals  
- Add items to cart  
- Place secure orders  
- Track order status  
- Receive OTP for delivery verification  

### For Sellers
- List products with details  
- Edit / delete inventory  
- Process orders  
- Generate delivery OTP  
- Track sales  

### Admin Capabilities
- User authentication management  
- Product CRUD operations  
- Order processing and tracking  
- Secure data handling  

---

## 🔒 Security Features
- Password hashing using **bcrypt**  
- JWT-based authentication  
- Protected API routes  
- Frontend & backend input validation  
- Secure CORS configuration  
- Environment variables for sensitive data  
- OTP-based delivery verification  

---

## 📱 Responsive Design
- Mobile-first layout  
- Touch-friendly UI  
- Adaptive design for tablets & desktops  
- Optimized image scaling  
- Cross-browser compatibility  

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

---

### Installation

```bash
git clone <your-repo-url>
cd "buy sell"

cd backend
npm install

MONGODB_URI=mongodb://localhost:27017/buysell
JWT_SECRET=your_jwt_secret_key
PORT=8080

npm run dev

cd ../frontend
npm install
npm start


📧 API Endpoints
Authentication

POST /api/users/register – Register user

POST /api/users/login – Login user

Products

GET /api/products/shop – Fetch products

POST /api/products/add – Add product

PUT /api/products/:id – Update product

DELETE /api/products/:id – Delete product

Cart & Orders

POST /api/products/addtocart – Add to cart

GET /api/products/cart – Get cart items

POST /api/orders/buynow – Place order

GET /api/orders/myorders – Order history

🤝 Contributing

Fork the repository

Create a feature branch

Commit your changes

Push to the branch

Open a Pull Request

👨‍💻 Author

Harshita Sharma
Full Stack Developer

⭐ Built with ❤️ using the MERN Stack

