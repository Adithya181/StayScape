# 🏡 StayScape

<div align="center">

![StayScape Banner](https://img.shields.io/badge/StayScape-Airbnb%20Clone-FF5A5F?style=for-the-badge&logo=airbnb&logoColor=white)

**A full-stack Airbnb-inspired vacation rental platform built with Node.js & MongoDB**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=flat-square&logo=ejs&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

</div>

---

## 📌 About

StayScape is a full-stack web application inspired by Airbnb. Users can explore property listings, view detailed information about each stay, and hosts can create, update, or remove their own listings. Built with a clean MVC architecture using Node.js, Express, EJS, and MongoDB.

---

## ✨ Features

- 🔍 **Browse Listings** — Explore all available rental properties at a glance
- 📋 **Listing Detail Page** — View full property info, location, price & description
- ➕ **Create a Listing** — Hosts can add new properties with all details
- ✏️ **Edit Listing** — Update your property info anytime
- 🗑️ **Delete Listing** — Remove listings you no longer want to offer
- 🌱 **Database Seeding** — Sample data pre-loaded for quick development setup
- ⚠️ **Custom Error Handling** — Graceful error pages for a smooth UX

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Runtime | Node.js |
| Framework | Express.js |
| Templating | EJS + EJS-Mate (layouts) |
| Database | MongoDB + Mongoose |
| Styling | Bootstrap 5 |
| Architecture | MVC (Model-View-Controller) |

---

## 📁 Folder Structure

```
StayScape/
├── 📂 Models/       → Mongoose data models
├── 📂 Views/        → EJS page templates
├── 📂 Layouts/      → Base layout wrappers
├── 📂 includes/     → Navbar, footer partials
├── 📂 init/         → DB seed scripts
├── app.js           → Express app entry point
├── error.js         → Custom error class
└── package.json     → Project dependencies
```

---

## ⚙️ Setup & Installation

```bash
# Clone the repo
git clone https://github.com/Adithya181/StayScape.git
cd StayScape

# Install dependencies
npm install

# Seed the database
node init/index.js

# Start the server
node app.js
```

Then open → **http://localhost:8080**

---

## 🔮 Upcoming Features

- [ ] 🔐 User Authentication & Authorization
- [ ] ⭐ Reviews & Ratings System
- [ ] 🔎 Search & Filter by location / price
- [ ] 🗺️ Map Integration (Mapbox)
- [ ] ☁️ Cloud Image Upload (Cloudinary)
- [ ] 📅 Booking & Reservation System

---

## 👥 Team

| | Member | GitHub |
|---|---|---|
| 👨‍💻 | Adithya | [@Adithya181](https://github.com/Adithya181) |
| 👨‍💻 | Sameer | [@sameermd07](https://github.com/sameermd07) |

---

<div align="center">
  <sub>Made with ❤️ by Adithya & Sameer</sub>
</div>
