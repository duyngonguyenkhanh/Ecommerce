# Ecommerce App

Ecommerce App is a full-stack web application designed for buying and managing Apple products. The project is divided into two main sections:

1. **Client**: A user-facing platform for browsing, searching, and ordering Apple products. Includes email confirmation for orders using Nodemailer and a live chat feature for customer support.  
2. **Admin**: Enables administrators to manage hotels (add, edit, delete), view all user transactions, and manage user accounts (including consultants and regular customers).

---

## 🌟 Demo

- **Client**: [Client Deployment Link](https://duyngonguyenkhanh.github.io/ecommerce-app/)  
- **Admin**: [Admin Deployment Link](https://duyngonguyenkhanh.github.io/admin-app/)  
- **Backend**: Deployed on [Render](https://render.com).

---

## 🚀 Key Features

### **Client**

- **Browse Products**:
  - View a list of Apple products with detailed descriptions and prices.
- **Search Products**:
  - Quickly find products by name or category.
- **Order Products**:
  - Add items to the cart and place orders with user details.
- **Email Confirmation**:
  - Receive an email confirmation of the order via **Nodemailer**.
- **Live Chat**:
  - Customers can chat with support staff (Admin or consultants) for real-time assistance.

### **Admin**

- **Role-based Access Control**:
  - **Admin**:
    - Manage products (add, edit, delete).
    - View, update, and delete orders.
    - Track revenue and manage user roles.
    - Oversee live chat interactions.
  - **Consultants**:
    - Respond to customer queries in live chat.
    - Assist with product recommendations and order issues.
- **Product Management**:
  - Add, edit, and delete product details (name, category, price, stock, etc.).
- **Order Management**:
  - View customer orders and update order statuses.
- **Revenue Tracking**:
  - Calculate and display total revenue from sales.

---

## 🛠️ Technologies Used

### **Frontend**
- **ReactJS**: For building user interfaces.  
- **React Router**: For navigation between pages.  
- **Tailwind CSS**: For responsive and modern styling.  
- **Socket.IO**: For real-time live chat.

### **Backend**
- **Node.js**: Server-side JavaScript runtime.  
- **Express.js**: For creating RESTful API endpoints.  
- **MongoDB**: For storing product, order, and user data.  
- **Nodemailer**: For sending email confirmations.  
- **Socket.IO**: For handling live chat communication.  
- **JWT**: For authentication and secure sessions.

### **Deployment**
- **Frontend**: Deployed on GitHub Pages or other hosting platforms.  
- **Backend**: Deployed on Render.

---

## 📁 Project Structure

```plaintext
ecommerce-app/
├── client/             # Frontend (ReactJS)
│   ├── public/         # Static files
│   ├── src/
│   │   ├── components/ # Reusable components
│   │   ├── pages/      # Client pages (Home, Product, Checkout, etc.)
│   │   ├── hooks/      # Custom hooks for logic handling
│   │   └── App.js      # Route configuration
├── admin/              # Admin Panel (ReactJS)
│   ├── src/
│   │   ├── components/ # Admin UI components
│   │   ├── pages/      # Admin pages (Dashboard, Manage Orders, etc.)
│   │   └── App.js      # Route configuration
├── server/             # Backend (Node.js)
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API routes
│   ├── controllers/    # API logic handlers
│   ├── sockets/        # Socket.IO for live chat
│   └── server.js       # Server entry point
└── README.md           # Project documentation
