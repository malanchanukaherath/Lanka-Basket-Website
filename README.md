# Lanka Basket: Full-Stack E-Commerce Platform

![GitHub Poster](https://github.com/user-attachments/assets/c071d46e-ed58-4459-87b9-57350ac82863)

Welcome to **Lanka Basket**, a full-featured online retail platform built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). Inspired by real-world Sri Lankan retail platforms such as Keells, Glomark, and Cargills Food City, this project includes multi-vendor support, secure authentication, cart management, order tracking, and an intuitive admin dashboard.

---

## Key Features

### User Features

- Register and log in with JWT authentication
- Browse products by categories
- Add and remove items from cart
- Checkout with shipping details
- Place orders
- View order history

### Admin Features

- Manage products, categories, and users
- View sales and orders
- Upload product images
- Dashboard with key metrics

### Other Highlights

- Responsive design (mobile-first)
- Toast notifications (React Hot Toast)
- Role-based access (user vs admin)
- SEO-friendly routing

---

## Tech Stack

| Frontend         | Backend    | Database | Tools           |
| ---------------- | ---------- | -------- | --------------- |
| React.js (Vite)  | Node.js    | MongoDB  | Redux Toolkit   |
| Tailwind CSS     | Express.js | Mongoose | Axios           |
| React Router DOM | JWT        |          | React Hot Toast |
| React Hook Form  | Stripe     |          | ESLint          |

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm
- MongoDB instance

### 1. Clone the Repository

```bash
git clone https://github.com/Chanith27/Lanka-Basket-Website.git
cd Lanka-Basket-Website
```

### 2. Configure Environment Variables

- Create the following files:
  - `client/.env`
  - `server/.env`
- Copy values from the provided example files:
  - `client/env.example`
  - `server/env.example`
- Replace example values with your own local credentials.
- Do not commit real keys or secrets to Git.

### 3. Install Dependencies

```bash
cd client
npm install
cd ../server
npm install
```

## Run the Project

### Frontend (Development)

```bash
cd client
npm run dev
```

### Backend (Development)

```bash
cd server
npm run dev
```

### Production Build and Start

Frontend build:

```bash
cd client
npm run build
```

Backend start:

```bash
cd server
npm start
```

## Project Documentation

### API Documentation

https://github.com/Chanith27/Lanka-Basket-Website/blob/main/API%20Documentation.pdf

### Unit Test Report

https://github.com/Chanith27/Lanka-Basket-Website/blob/main/Backend%20Test%20Report.pdf

## Team Member Contributions

- **A.M.C.R.P. Adikari (IM/2022/004)** - Led frontend client development, focusing on UI design and integration using React.js and Tailwind CSS.
- **B.M.N.N. Bandara (IM/2022/050)** - Contributed to server and admin-side UI, including order controllers, payment integration, and key admin components.
- **W.M.A.M. Madushan (IM/2022/025)** - Designed and implemented the overall backend server structure.
- **J.M.T. Sanjana (IM/2022/130)** - Developed components and backend routes for product and order management, including editing, viewing, and alert notifications.
- **H.M.M.C.H. Herath (IM/2022/057)** - Managed file uploads, middleware, category routing, Dockerized the application, and supported application hosting tasks.
