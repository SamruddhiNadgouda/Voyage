# ✈️ Voyage — End-to-End Destination Guide

> *End-to-end destination guide for your next adventurous trip.*

**Voyage** is a full-stack web application built with **Node.js**, **Express**, **MongoDB**, and **EJS** that helps users explore and manage travel destinations. It follows the MVC (Model-View-Controller) architecture pattern for clean, maintainable code.

---

## 📌 Project Overview

Voyage is a travel destination guide platform where users can browse, add, and manage trip destinations. Built with a server-side rendered approach using EJS templates, it connects to a MongoDB database to store and retrieve destination data.

---

## ✨ Features

- 🗺️ **Destination Listings** — Browse a collection of travel destinations
- ➕ **Add Destinations** — Create and submit new destination entries
- ✏️ **Edit & Delete** — Update or remove existing destinations (via method-override)
- 🎨 **Templated Views** — Consistent layouts using EJS-Mate for reusable templates
- 🗄️ **Database Integration** — Persistent storage with MongoDB via Mongoose
- 📦 **Seed Data** — Initial data seeding via the `init` folder

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Node.js | Server-side runtime |
| Express.js | Web framework and routing |
| MongoDB | NoSQL database |
| Mongoose | MongoDB ODM for schema/models |
| EJS | Server-side HTML templating |
| EJS-Mate | Layout/partial support for EJS |
| Method-Override | Enables PUT/DELETE from HTML forms |
| CSS | Custom frontend styling |

---

## 📁 File Structure

```
Voyage/
│
├── init/               # Seed data for initializing the database
├── models/             # Mongoose schemas and models
├── public/
│   └── css/            # Custom stylesheets
├── views/              # EJS templates and layouts
├── app.js              # Main Express application entry point
├── package.json        # Project dependencies
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or above)
- [MongoDB](https://www.mongodb.com/) (local or Atlas cloud)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/SamruddhiNadgouda/Voyage.git
   cd Voyage
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start MongoDB** (if running locally)
   ```bash
   mongod
   ```

4. **Seed initial data** (optional)
   ```bash
   node init/index.js
   ```

5. **Run the application**
   ```bash
   node app.js
   ```

6. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 📦 Dependencies

```json
{
  "ejs": "^3.1.10",
  "ejs-mate": "^4.0.0",
  "express": "^4.19.2",
  "method-override": "^3.0.0",
  "mongoose": "^8.5.3"
}
```

---

## 🙋‍♀️ Author

**Samruddhi Nadgouda**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/samruddhi-nadgouda/)
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)](https://github.com/SamruddhiNadgouda)
