# Furniture Backend Project

A scalable and secure backend API for a Furniture eCommerce platform built using Node.js, Express.js, and MongoDB.

---

## Features

- User Authentication & Authorization
- JWT Security
- Furniture Product Management
- Category Management
- Order Management
- Admin Dashboard APIs
- Image Upload Support
- RESTful API Architecture
- MongoDB Database Integration
- Error Handling Middleware

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt.js
- Multer
- dotenv

---

## Folder Structure

```bash
furniture-backend/
│
├── controllers/
├── middleware/
├── models/
├── routes/
├── config/
├── uploads/
├── utils/
├── .env
├── server.js
├── package.json
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/furniture-backend.git
```

### Move to Project Folder

```bash
cd furniture-backend
```

### Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development
```

---

## Run Project

### Development Mode

```bash
npm run dev
```

### Production Mode

```bash
npm start
```

Server Running On:

```bash
http://localhost:5000
```

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register User |
| POST | /api/auth/login | Login User |

---

### Products

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/products | Get All Products |
| GET | /api/products/:id | Get Single Product |
| POST | /api/products | Create Product |
| PUT | /api/products/:id | Update Product |
| DELETE | /api/products/:id | Delete Product |

---

### Orders

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/orders | Create Order |
| GET | /api/orders | Get Orders |
| GET | /api/orders/:id | Get Single Order |

---

## JWT Authentication

Add token in request headers:

```http
Authorization: Bearer your_token
```

---

## GitHub Upload Commands

### Initialize Git

```bash
git init
```

### Add Files

```bash
git add .
```

### Commit Files

```bash
git commit -m "Initial Commit"
```

### Add GitHub Repository

```bash
git remote add origin https://github.com/your-username/furniture-backend.git
```

### Push Code

```bash
git branch -M main
git push -u origin main
```

---

## Future Improvements

- Payment Gateway Integration
- Product Reviews & Ratings
- Wishlist Feature
- Inventory Management
- Email Notifications
- Docker Deployment

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by -AHMAD RAJA
