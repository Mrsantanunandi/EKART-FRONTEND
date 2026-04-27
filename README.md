# 🛒 Ekart – Full Stack E-Commerce Application

![AWS Elastic Beanstalk](https://img.shields.io/badge/Backend-AWS%20Elastic%20Beanstalk-orange?logo=amazon-aws\&logoColor=white)
![Railway](https://img.shields.io/badge/Backend-Railway-purple?logo=railway\&logoColor=white)
![Vercel](https://img.shields.io/badge/Frontend-Vercel-black?logo=vercel\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Backend-brightgreen?logo=springboot)
![React](https://img.shields.io/badge/React-Frontend-blue?logo=react)

---

## 🔗 Live Links

**Frontend (Vercel)**
👉 [https://frolicking-starburst-33437b.netlify.app/](https://frolicking-starburst-33437b.netlify.app/)

**Backend API**
✅ Deployed on **AWS Elastic Beanstalk**
✅ Also deployed on **Railway**
🔄 **Currently connected and running via AWS ELASTIC BEANSTALK backend**

---

## 📌 About the Project

Ekart is a **production-ready full-stack e-commerce web application** built using **React** for the frontend and **Spring Boot** for the backend.

The application follows **industry-level security practices** and supports **role-based access control**, **secure online payments**, **email verification**, and a **complete admin analytics dashboard**.

This project demonstrates real-world implementation of **authentication**, **authorization**, **cloud image storage**, **payment gateways**, **database management**, and **multi-cloud backend deployment using AWS and Railway**.

---

## 🧑‍💻 Tech Stack

### Frontend

* React (Vite)
* Redux Toolkit
* Axios
* Tailwind CSS
* ShadCN UI
* Chart libraries for admin analytics
* Vercel for deployment

### Backend

* Spring Boot
* Spring Security
* JWT Authentication
* Hibernate / JPA
* PostgreSQL Database
* Razorpay Payment Gateway
* Cloudinary Image Storage
* **AWS Elastic Beanstalk**


---

## 🔐 Security and Authentication

* JWT-based authentication
* Role-based authorization (USER and ADMIN)
* Password encryption using BCrypt
* Email verification during user signup
* OTP-based password reset system
* Stateless session management
* Protected REST APIs using Spring Security
* Secure Razorpay payment authentication

---

## ✨ Application Features

### 👤 User Features

* User registration with email verification
* Secure login using JWT
* Encrypted password storage
* Forgot password and OTP-based reset
* Update personal profile details
* Upload profile image using Cloudinary
* Browse available products
* Add products to cart
* Secure checkout using Razorpay
* View order history
* Track personal orders

### 🛠 Admin Features

* Admin authentication and authorization
* Admin dashboard with analytics
* View total users, orders, and sales
* Graph-based sales and order visualization
* Add new products
* Update existing product details
* Delete products
* Upload product images using Cloudinary
* View all user profiles
* Manage and view all user orders

---

## 📊 Admin Dashboard Analytics

* Total sales overview
* Total orders count
* User growth tracking
* Graphical representation of orders and revenue
* Fully protected admin routes

---

## 💳 Payment Integration

* Razorpay payment gateway integration
* Secure order creation and verification
* Backend payment signature verification
* Transaction-safe order placement

---

## 🖼 Image Upload System

* Cloudinary integration
* User profile image upload
* Product image upload
* Secure cloud storage
* Optimized image delivery

---

## 🗄 Database

* PostgreSQL production database
* JPA and Hibernate ORM
* Optimized entity relationships
* Secure and scalable schema design

---

## ⚙️ Environment Variables

### Frontend (.env)

```env
VITE_URL=https://your-backend-api-url
VITE_RAZORPAY_KEY=your_razorpay_key
```

### Backend (application.properties)

```properties
spring.datasource.url=jdbc:postgresql://<host>:5432/ekart
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password

jwt.secret=your_jwt_secret

cloudinary.cloud-name=your_cloud_name
cloudinary.api-key=your_api_key
cloudinary.api-secret=your_api_secret

razorpay.key=your_razorpay_key
razorpay.secret=your_razorpay_secret
```

---

## 🚀 Deployment Details

### Frontend

* Platform: Vercel
* Build command: npm run build
* Output directory: dist
* Environment variables configured in Vercel dashboard

### Backend

* Platforms:

  * AWS Elastic Beanstalk
  * Railway
* Spring Boot JAR deployment
* PostgreSQL database
* Environment variables configured in cloud dashboards
* **Currently active backend: Railway**
* Fully live and production-ready

---

## 🧪 Run the Project Locally

### Frontend

```bash
npm install
npm run dev
```

### Backend

```bash
mvn clean install
java -jar target/ekart.jar
```

---

## 📁 Frontend Project Structure

```bash
src/
├── components/
├── pages/
├── redux/
├── axiosWithJwt.js
├── App.jsx
└── main.jsx
```

---

## 🎯 Learning Outcomes

* Full-stack application architecture
* JWT authentication with Spring Security
* Razorpay payment gateway integration
* Secure email verification system
* Cloudinary image handling
* Admin dashboard analytics
* PostgreSQL database management
* **Multi-cloud backend deployment (AWS + Railway)**
* Production-grade security practices

---

## 👨‍🎓 Author

**Santanu Nandi**
B.Tech in Computer Science and Engineering

---

## ⭐ Support

If you find this project helpful or impressive, please give the repository a ⭐ on GitHub.
Your support is highly appreciated and motivating 🚀
