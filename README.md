# 🛍️ Shoppy - E-Commerce Web Platform

A complete modern e-commerce web platform built with the MERN Stack. Shoppy allows users to browse products, manage carts, place orders, and track deliveries. Admins can manage inventory, users, and analytics through a powerful dashboard.

---

## 🚀 Features

- 🛒 Product Browsing & Filtering
- 🔍 Search Functionality
- 🧺 Cart Management
- 🔐 User Authentication (Login/Register)
- 💳 Order Placement & Payment Gateway Ready
- 📦 Order Tracking
- 🧑‍💼 Admin Dashboard for Product & User Management
- 📱 Fully Responsive Design
- 📈 Sales Analytics (Admin Panel)

---

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS, Redux Toolkit, Axios  
**Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT, Bcrypt  
**Admin Panel:** Built into same React frontend with role-based access

---

## 🔧 Setup Instructions

1. Clone the repository and move into the project:

   `git clone https://github.com/yourusername/shoppy-ecommerce.git && cd shoppy-ecommerce`

2. Set up the backend:

   `cd backend && npm install && npm run dev`

3. Open a new terminal, then set up the frontend:

   `cd frontend && npm install && npm start`

4. Create a `.env` file in the `/backend` directory and add the following:

   `MONGO_URI=your_mongodb_connection_string`  
   `JWT_SECRET=your_jwt_secret`  
   `PAYMENT_GATEWAY_KEY=your_payment_gateway_key` *(optional)*

---

## 🧠 Folder Structure
shoppy-ecommerce/ ├── backend/ # Express.js API + MongoDB + Auth + Order Logic ├── frontend/ # React.js UI + Redux for Cart & Orders └── admin/ 

## 🌐 Live Demo

🔗 Coming Soon  
➡️ Deploy frontend on [Vercel](https://vercel.com)  
➡️ Deploy backend on [Render](https://render.com) or [Railway](https://railway.app)

---

## 📸 Screenshots

| Home Page | Product Page | Admin Dashboard |
|-----------|---------------|------------------|
| ![Home](./screenshots/home.png) | ![Product](./screenshots/product.png) | ![Admin](./screenshots/admin.png) |

---

## 🙌 Contributing

Contributions are welcome!  
Feel free to fork the repo and submit a pull request with improvements.

---

## 📄 License

Licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---

## 👨‍💻 Developed By

**Harsh Sharma**  
Aspiring Full Stack Developer | Entrepreneur in the Making 🚀  
[LinkedIn](https://www.linkedin.com/in/harsh41sharma) • [GitHub](https://github.com/harsh41sharma)
