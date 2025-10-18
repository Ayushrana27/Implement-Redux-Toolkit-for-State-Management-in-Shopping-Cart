# 🛒 React + Redux Toolkit Shopping Cart App

Welcome to the **RoadWare Product Store** 🚗 — a sleek React application built using **Redux Toolkit** for state management.  
It allows users to browse products, add them to a cart, update quantities, and remove items — with instant UI updates ⚡

---

## 🌟 Features

✅ Add products to cart  
✅ Update product quantity directly  
✅ Remove products easily  
✅ View total price dynamically  
✅ Global cart state managed by Redux Toolkit  

---

## 🧠 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend  | ⚛️ React.js |
| State Management | 🧰 Redux Toolkit |
| Styling | 💅 Inline CSS |
| Hooks Used | `useSelector`, `useDispatch` |

---

## 📁 Folder Structure
redux-cart/
├── src/
│ ├── app/
│ │ └── store.js
│ ├── features/
│ │ ├── cart/
│ │ │ ├── cartSlice.js
│ │ │ └── Cart.jsx
│ │ └── products/
│ │ └── ProductList.jsx
│ ├── App.js
│ └── index.js
└── package.json



## ⚙️ Installation & Setup Guide

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/redux-cart.git
cd redux-cart

2️⃣ Install dependencies
npm install

3️⃣ Start the development server
npm start


Then visit 👉 http://localhost:3000

💼 Usage
🛍️ Browse Products

View all products from RoadWare, each showing a name, price, and “Add to Cart” button.

➕ Add to Cart

Click “Add to Cart” to add the product globally using Redux Toolkit.

🔄 Update Quantity

Change product quantity directly in the cart. The total updates instantly!

❌ Remove from Cart

Easily remove unwanted items with a single click.

🧩 Redux Flow Diagram
ProductList.jsx
   ⬇ dispatch(addToCart)
store.js
   ⬇
cartSlice.js  <-- manages add, remove, update logic
   ⬆
Cart.jsx (useSelector to fetch state)

📸 Screenshots (Add your own)
Product Page	Cart Page

	
🚀 Key Learnings

Implementing Redux Toolkit slices

Using react-redux hooks for state access

Managing and syncing UI with global store

Designing modular React components

🧑‍💻 Developed By

Ayush Rana
🎓 Computer Science Engineer @ Chandigarh University
🚀 Passionate about React, Redux, and Embedded Systems

💬 Feedback

Got ideas or feedback?
Drop an issue or PR on GitHub — contributions are always welcome! 🌱
