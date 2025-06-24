# Fusion Electronics: A MERN-Stack E-commerce Application

Welcome to **Fusion Electronics**, a **MERN-Stack E-commerce Application**! This project is a working demo of a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It demonstrates the development of a modern e-commerce platform, covering frontend user interface, backend server logic, database management, and integration with third-party libraries.

---

## Live Deployment

- **Frontend:** [Fusion Electronics (Vercel)](https://fusion-ecommerce-app.vercel.app)
- **Backend:** [Fusion Electronics API (Render)](https://mern-stack-ecommerce-app-h5wb.onrender.com/)

> ⚠️ **Note**: The backend server may take a few seconds to wake up if it has been inactive, as it is hosted on the free Render tier.

---

## Features

### 🛒 Product Management
- Browse product catalog
- View detailed product pages
- Search for products

### 🛍️ Shopping Cart
- Add/remove products
- View total price
- Quantity management

### 💳 Checkout Process
- Form validation (billing/shipping/payment)
- Order confirmation page

### 🔐 Authentication
- Login, Register, Forgot & Reset Password flows
- JWT-based user authentication
- Password hashing via Bcrypt

### 🧰 Admin Functionality (Optional)
- Product listing control
- Order status management *(extendable)*

### 📑 API Documentation
- Swagger UI at `/api-docs` for REST API testing and documentation

---

## Technologies Used

### Frontend:
- React.js, Material-UI, Axios, React Router
- Form Validation: `react-hook-form`
- Credit Card Input: `react-credit-cards-2`
- Toast Notifications: `react-toastify`

### Backend:
- Node.js, Express.js
- MongoDB + Mongoose
- JWT Auth, Bcrypt for password security
- Swagger for API documentation

---

## Project Structure (High-Level)

fullstack-ecommerce/
├── backend/ # Node.js & Express server
├── public/ # Frontend public assets
├── src/ # React frontend
├── docs/ # UI screenshots & swagger images
├── tests/ # Testing (Jest)
├── openapi.yaml # API spec


---

## Swagger API Docs

API docs available at:


You can also test using:
- [Swagger Editor](https://editor.swagger.io/)
- [Postman](https://www.postman.com/) by importing `openapi.yaml`

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Creator

- **Krishna Kolarya** – [krish-kolarya](https://github.com/krish-kolarya)  
- **Email:** [krishnakolarya@gmail.com](mailto:krishnakolarya@gmail.com)

---

Thank you for checking out **Fusion Electronics**! If you enjoyed the project, feel free to ⭐️ the repo or contribute.
