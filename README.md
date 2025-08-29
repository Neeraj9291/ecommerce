# 🛍️ Multi-Vendor eCommerce Platform

This is a backend for a multi-vendor eCommerce platform where sellers can:
- Create profiles
- List their products
- Allow product filtering
- View vendor ratings and profiles

The backend is built with **Node.js and Express.js**, and is designed to support future frontend integrations (e.g., React, Vue, Angular).

---

## 📁 Project Structure

├── models/ # MongoDB models (e.g., User, Product)
├── routes/ # API route handlers
├── server.js # Main Express server entry point
├── .env # Environment variables
├── .gitignore
├── package.json
---

## 🚀 Features

- Vendor authentication and profile management
- Product listing per vendor
- Product filtering
- Ratings and vendor pages
- Modular structure for easy scaling

---

## 🧰 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB** (assumed)
- **Mongoose** (if you're using ODM)
- **dotenv** for environment variables

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/Neeraj9291/ecommerce.git

# Navigate to the folder
cd ecommerce

# Install dependencies
npm install

# Run the server
npm start
PORT=5000
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_jwt_secret_key
