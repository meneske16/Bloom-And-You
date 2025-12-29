# 🌸 Bloom & You — MERN Stack E-Commerce Project

**Bloom & You** is a mindful self-care e-commerce web application built using the MERN stack. It features a customizable collection of wellness products like scented candles, bath bombs, and skincare, designed to bring tranquility to your daily routine.

This project was developed as the **Final Group Project** for the Web Technologies course.

## 🚀 Live Demo

- **Frontend (Netlify):** [https://bloomandyou.netlify.app/](https://bloomandyou.netlify.app/)
- **Backend (API):** *(Add your Render/Railway Link Here or keep 'Localhost' for now)*

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Vite/CRA)
- React Router DOM (Navigation)
- Context API (State Management for Cart)
- CSS3 (Custom Styling, Responsive Design)

**Backend:**
- Node.js
- Express.js
- Mongoose (ODM)
- CORS & Dotenv

**Database:**
- MongoDB Atlas (Cloud Database)

---

## ✨ Key Features

1.  **Product Browsing:**
    - Categorized products (Scented Candles, Bath Bombs, Pajamas, Skincare, Bouquets).
    - Dynamic routing for product categories.
    
2.  **Shopping Cart System:**
    - Add to cart functionality using Context API.
    - View total price and manage items in the cart.

3.  **User Authentication (Forms):**
    - **Login & Sign Up:** Controlled forms with state management and validation.
    - Toggle between login/register views seamlessly.

4.  **Checkout Process:**
    - **Checkout Form:** Collects shipping details (Name, Address, City) before order placement.

5.  **Contact Support:**
    - **Contact Form:** Functional form that sends user messages to the backend database.

6.  **Responsive Design:**
    - Fully responsive layout for mobile, tablet, and desktop views.

---

## 📂 Project Structure

```

root
├── client/              # Frontend (React)
│   ├── src/
│   │   ├── components/  # Reusable components
│   │   ├── context/     # CartContext logic
│   │   ├── pages/       # Home, Contact, Account, Checkout, etc.
│   │   ├── styles/      # CSS files
│   │   └── App.jsx      # Main Route definitions
│   └── ...
│
├── server/              # Backend (Node/Express)
│   ├── models/          # Mongoose Schemas (User, Contact, Order)
│   ├── routes/          # API Routes
│   ├── index.js         # Server entry point
│   └── .env             # Environment variables
└── README.md

````

---

## ⚙️ Installation & Run Locally

Follow these steps to run the project on your local machine.

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/bloom-and-you.git
cd bloom-and-you
````

### 2. Backend Setup

Navigate to the server folder and install dependencies:

```bash
cd server
npm install
```

Create a `.env` file in the `server` folder and add your MongoDB connection:

```env
MONGO_URI=mongodb+srv://<your_db_user>:<password>@cluster.mongodb.net/bloomandyou?retryWrites=true&w=majority
PORT=5000
```

Start the server:

```bash
npm start
# Server runs on http://localhost:5000
```

### 3. Frontend Setup

Open a new terminal, navigate to the client folder, and install dependencies:

```bash
cd client
npm install
```

Start the React app:

```bash
npm run dev
# Frontend runs on http://localhost:5173 (or 3000)
```

---

## 📡 API Endpoints

| Method   | Endpoint             | Description                   |
| -------- | -------------------- | ----------------------------- |
| **GET**  | `/api/products`      | Fetch all products            |
| **POST** | `/api/contact`       | Submit a contact form message |
| **POST** | `/api/auth/register` | Register a new user           |
| **POST** | `/api/auth/login`    | Login a user                  |
| **POST** | `/api/orders`        | Place a new order             |

---

## 👥 Group Members

| Name                | Role                 | GitHub                           |
| ------------------- | -------------------- | -------------------------------- |
| **Minahil Nadeem**  | Full Stack Developer | [@username](https://github.com/) |

