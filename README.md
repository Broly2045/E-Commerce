# 🛒 E-Comm Shop

E-Comm Shop is a full-stack e-commerce web application built to understand and implement core online shopping functionality.  
The project focuses on product listing, cart management, server-side rendering, and backend routing using Node.js and Express.

This project was developed as a learning-focused full-stack application while practicing real-world e-commerce workflows.

---

## ✨ Features

- Product listing with images and pricing
- Add to cart and remove from cart functionality
- Cart total calculation
- Server-side rendered views
- Modular backend architecture
- Basic admin and product routes
- Input validation and middleware usage

---

## 🧑‍💻 Tech Stack

### Backend
- Node.js
- Express.js
- Express Validator
- Cookie-based sessions

### Frontend
- HTML
- CSS
- Server-side templates (views)

### Tools & Libraries
- Multer (file uploads)
- Nodemon
- Git & GitHub

---

## 📁 Project Structure

e-comm/
├── public/ # Static assets (CSS, images)
├── repositories/ # Data access logic
│ ├── products.js
│ ├── carts.js
│ └── users.js
├── routes/ # Application routes
│ ├── products.js
│ ├── carts.js
│ └── admin/
├── views/ # Server-rendered UI
│ ├── products/
│ ├── carts/
│ └── admin/
├── helpers.js
├── index.js
└── package.json

---

## 🔄 How the Application Works

- Products are rendered on the homepage
- Users can add products to the cart
- Cart page displays selected items and total price
- Users can remove items from the cart
- Backend routes handle product and cart logic
- Views are rendered dynamically using server-side templates

---
## ⚙️ Setup & Run Locally

1️⃣ Clone the Repository
git clone https://github.com/Broly2045/E-Commerce.git
cd E-Commerce

2️⃣ Install Dependencies
npm install

3️⃣ Start the Development Server
npm run dev

4️⃣ Open in Browser
Open your browser and visit:
http://localhost:3000

