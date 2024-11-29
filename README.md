# Server - E-commerce Cart System

This is the **Backend** of the E-commerce Cart System, built with Node.js and Express.js. It handles API requests, business logic, and database operations.

---

## **Features**
- CRUD operations for products:
  - Add, edit, delete, and list products.
- Cart management:
  - Add, update, or remove items in the cart.
- Process payments and maintain order history.
- Validates user inputs to ensure data integrity.

---

## **Technologies Used**
- **Backend Framework:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** JWT

---

## **Setup Instructions**

### Prerequisites
- Node.js installed on your machine.
- MongoDB installed and running (local or cloud-based, e.g., MongoDB Atlas).

---

### Steps to Run the Backend
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
2. **Navigate to the Backend Folder**:
   ```bash
   cd cirrolink-server
3. **Install Dependencies**:
   ```bash
    npm install
4. **Environment Variables: Create a .env file in the backend folder with the following content**:
   ```bash
   PORT = 5000
   MONGO_STRING = mongodb+srv://jithya1504:jithya1504@e-commerce.c81bgia.mongodb.net/?retryWrites=true&w=majority&appName=e-commerce
   JWT_SECRET = 123
5. **Start the Backend Server**:
   ```bash
   npm start
6. **API Base URL**:
   The server will run at: http://localhost:5000
