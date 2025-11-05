# 📘 **Read for Change**

## 📝 Overview

**Problem:** Many learners struggle to find reliable and inspiring educational books that foster growth and learning.

**Solution:** *Read for Change* is a web platform that promotes **SDG 4: Quality Education** by enabling users to explore, review, and recommend educational or inspirational books. It builds a community that shares trusted learning resources and encourages a culture of reading and continuous education.

---

## 💻 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js (Express.js)
* **Database:** MySQL
* **API Integration:** Google Books API

---

## ⚙️ Setup Instructions

### 🔹 Backend Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/read-for-change.git
   cd read-for-change/backend
   ```
2. **Install dependencies and run**

   ```bash
   npm install
   npm run dev
   ```
3. **Database setup**

   * Create a MySQL database (e.g., `read_for_change_db`)
   * Import `schema.sql` located in the `/database` folder
4. **Backend URL**

   ```
   http://localhost:5000
   ```

---

### 🔹 Frontend Setup

1. Navigate to the frontend folder

   ```bash
   cd ../frontend
   ```
2. Open `index.html` in your browser
3. Adjust any `fetch()` API URLs in JavaScript files if needed (e.g., `http://localhost:5000/api/...`)

---

## ✨ Features

* [x] **User Authentication** (JWT-secured Register/Login)
* [x] **CRUD Operations** (Create, Read, Update, Delete reviews)
* [x] **Google Books API Integration** (fetch book details automatically)
* [x] **Educational Focus** (promotes literacy and lifelong learning)

---

## 👩‍💻 Contributors

| Name           | Role                 | Responsibilities                                                    |
| -------------- | -------------------- | ------------------------------------------------------------------- |
| **Sara Hailu** | Full Stack Developer | Backend API, Database design, Frontend integration, API integration |

