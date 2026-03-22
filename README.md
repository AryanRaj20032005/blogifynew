# 📝 Blogify - Full Stack Blog Application

🚀 Blogify is a modern full-stack blogging platform where users can create, read, and manage blog posts with a clean and responsive UI.

---

## 🌟 Features

* 🏠 Home page displaying all blogs
* ✍️ Create and publish new blog posts
* 🧾 Add title, description, and cover image
* 👤 User authentication (Login / Signup UI)
* 📚 View personal blogs (My Blogs)
* 🗑️ Delete and manage blogs (if implemented)
* ⚡ Fast and responsive UI

---

## 🛠️ Tech Stack

### 💻 Frontend

* React.js
* Vite
* Axios
* CSS (Custom Styling)

### ⚙️ Backend

* Node.js
* Express.js

### 🗄️ Database

* MongoDB (Mongoose)

---

## 📂 Project Structure

```
blogifynew/
│── client/        # Frontend (React App)
│── server/        # Backend (Express API)
│── app.js         # Main backend entry point
│── connection.js  # MongoDB connection
│── package.json
```

---

## ⚙️ Getting Started

### 📌 Prerequisites

Make sure you have installed:

* Node.js
* npm
* MongoDB (local or MongoDB Atlas)

---

## 🔧 Installation

```bash
# Clone repository
git clone https://github.com/AryanRaj20032005/blogifynew.git

# Navigate to project directory
cd blogifynew

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

Create a `.env` file in the root directory:

```env
MONGO_URI=mongodb://127.0.0.1:27017/blogify
PORT=3000
```

---

## 🔗 API Endpoints

| Method | Endpoint   | Description       |
| ------ | ---------- | ----------------- |
| GET    | /blogs     | Get all blogs     |
| POST   | /blogs     | Create a new blog |
| GET    | /blogs/:id | Get a single blog |
| DELETE | /blogs/:id | Delete a blog     |

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
