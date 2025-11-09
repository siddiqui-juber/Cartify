# 🛒 CartiFy — Full Stack E-Commerce Application

**Cartify** is a complete e-commerce web application developed to showcase secure backend development using **Java Spring Boot** and a responsive frontend using **React.js**. The project demonstrates authentication, product management, category filtering, and real-time cart handling.

---

## 🚀 Features

### 👨‍💻 Backend (Spring Boot)

* RESTful APIs for Products, Categories, and Authentication
* **JWT-based Authentication** with role-based access (Admin/User)
* Product CRUD Operations (Admin only)
* Secure CORS configuration for frontend integration
* MySQL database integration using Spring Data JPA

### 💻 Frontend (React.js)

* Product listing with **search and category filtering**
* Shopping Cart using React Context
* Light/Dark theme toggle
* Responsive UI with Bootstrap 5

---

## 🧩 Tech Stack

| Layer        | Technologies                            |
| ------------ | --------------------------------------- |
| **Frontend** | React.js, Axios, Bootstrap              |
| **Backend**  | Spring Boot, Spring Security (JWT), JPA |
| **Database** | MySQL                                   |
| **Tools**    | IntelliJ IDEA, Postman, VS Code         |

---

## ⚙️ API Endpoints

### 🔐 Auth

| Method | Endpoint             | Description       |
| ------ | -------------------- | ----------------- |
| POST   | `/api/auth/login`    | User login        |
| POST   | `/api/auth/register` | Register new user |

### 🛍️ Products

| Method | Endpoint                            | Access | Description             |
| ------ | ----------------------------------- | ------ | ----------------------- |
| GET    | `/api/product`                      | Public | Get all products        |
| GET    | `/api/product/{id}`                 | Public | Get product by ID       |
| POST   | `/api/product`                      | Admin  | Add a new product       |
| PUT    | `/api/product/{id}`                 | Admin  | Update a product        |
| DELETE | `/api/product/{id}`                 | Admin  | Delete a product        |
| GET    | `/api/product/search?keyword=phone` | Public | Search products by name |

### 🗂️ Categories

| Method | Endpoint        | Access | Description        |
| ------ | --------------- | ------ | ------------------ |
| GET    | `/api/category` | Public | Get all categories |
| POST   | `/api/category` | Admin  | Add a new category |

---

## 🧠 What I Learned

* Implementing **Spring Security + JWT** from scratch
* Building a layered backend structure (**Controller → Service → Repository**)
* Handling **CORS and 403 Forbidden** issues between frontend and backend
* Integrating secure REST APIs with React
* Writing **clean, reusable, and maintainable code**

---



---

## 🧑‍💻 Author

**Siddique Jubair**
💼 Java Backend Developer
🌐 [LinkedIn]linkedin.com/in/juber-ahmad-siddiqui-77841b2bb


---

## 🏷️ Tags

`Java` `Spring Boot` `React.js` `MySQL` `JWT` `Full Stack Development` `E-Commerce` `REST API`

---

> ⚡ *Built with a focus on Java Backend Development, clean architecture, and practical integration between Spring Boot and React.*
