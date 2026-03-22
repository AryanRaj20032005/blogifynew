# 📝 Blogify - Full Stack Blog Application

🚀 Blogify is a modern full-stack blogging platform where users can create, read, and manage blog posts with a clean and responsive UI.

---

## 🌟 Features

* 🏠 Home page with all blogs
* ✍️ Create new blog posts
* 🧾 Add title, description & cover image
* 👤 User authentication (Login / Signup UI)
* 📚 View personal blogs (My Blog)
* 🗑️ Delete / manage blogs (if implemented)
* ⚡ Fast and responsive UI

---

## 🛠️ Tech Stack

### 💻 Frontend

* React.js
* Vite
* Axios
* CSS (Custom styling)

### ⚙️ Backend

* Node.js
* Express.js

### 🗄️ Database

* MongoDB (Mongoose)

---

## 📂 Project Structure

```
blogify/
│── client/        # Frontend (React App)
│── server/        # Backend (Express API)
│── app.js         # Main backend file
│── connection.js  # MongoDB connection
│── package.json
```

---

## ⚙️ Getting Started

### 📌 Prerequisites

Make sure you have installed:

* Node.js
* npm
* MongoDB (local or Atlas)

---

## 🔧 Installation

```bash
# Clone repository
git clone https://github.com/AryanRaj20032005/blogifynew.git

# Navigate to project
cd blogify

# Install backend dependencies
npm install
```

---

## ▶️ Run Backend

```bash
node app.js
```

---

## ▶️ Run Frontend

```bash
cd client
npm install
npm run dev
```

---

## 🌍 Environment Variables

Create a `.env` file in root:

```env
MONGO_URI=mongodb://127.0.0.1:27017/blogify
PORT=3000
```

---

## 🔗 API Endpoints

| Method | Endpoint   | Description     |
| ------ | ---------- | --------------- |
| GET    | /blogs     | Get all blogs   |
| POST   | /blogs     | Create blog     |
| GET    | /blogs/:id | Get single blog |
| DELETE | /blogs/:id | Delete blog     |

---

## 📸 Screenshots

*Add your screenshots here*

---

## 👨‍💻 Author

**Aryan Raj**
🔗 GitHub: https://github.com/AryanRaj20032005

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 🚀 Future Improvements

* 🔐 JWT Authentication
* ❤️ Like & Comment system
* 📷 Image upload (Cloudinary)
* 🌐 Deployment (Vercel / Render)
