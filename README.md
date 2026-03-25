# 🏡 UrbanHaven

UrbanHaven is a full-stack web application for browsing and managing property listings. It uses server-side rendering with EJS to deliver dynamic content efficiently.

🔗 Live Demo: https://urbanhaven.onrender.com/listings

---

## 🚀 Features

* 🏘️ Browse all property listings
* ➕ Create new listings
* 📝 Edit existing listings
* 🗑️ Delete listings
* 🎨 Server-side rendered UI using EJS
* ☁️ Deployed on cloud (Render)
* 🗺️ Map integration for listings

---

## 🛠️ Tech Stack

### Backend

* Node.js
* Express.js

### Frontend (Templating)

* EJS (Embedded JavaScript Templates)
* HTML, CSS

### Database

* MongoDB Atlas

### Deployment

* Render

---

## 📂 Project Structure

```id="4w7lbn"
.
├── models/         # Mongoose schemas
├── routes/         # Express routes
├── controllers/    # Logic for routes
├── views/          # EJS templates
│   ├── listings/
│   ├── partials/
│   └── layouts/
├── public/         # Static files (CSS, JS)
├── app.js          # Main server file
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```id="d0crd5"
git clone https://github.com/your-username/urbanhaven.git
cd urbanhaven
```

### 2. Install dependencies

```id="dfx2cf"
npm install
```

### 3. Setup environment variables

Create a `.env` file:

```id="8v8g9p"
ATLAS_URL=your_mongodb_connection_string
PORT=3000
```

### 4. Run the app

```id="n0ll9t"
npm start
```

---

## 🌐 Routes Overview

| Method | Route              | Description            |
| ------ | ------------------ | ---------------------- |
| GET    | /listings          | Show all listings      |
| GET    | /listings/new      | Form to create listing |
| POST   | /listings          | Create listing         |
| GET    | /listings/:id      | Show single listing    |
| GET    | /listings/:id/edit | Edit form              |
| PUT    | /listings/:id      | Update listing         |
| DELETE | /listings/:id      | Delete listing         |

---

## 🧠 Key Concepts Used

* Server-side rendering with EJS
* RESTful routing
* MVC architecture
* MongoDB with Mongoose
* Deployment debugging (502 errors & DB connection issues)

---

## 🔐 Environment Variables

* `ATLAS_URL` → MongoDB connection string
* `PORT` → Server port

---

## 📌 Future Improvements

* 🔐 User authentication (JWT / sessions)
* 📸 Image upload support

* ❤️ Favorites system
* 🔍 Search & filtering

---

## 📜 License

MIT License
