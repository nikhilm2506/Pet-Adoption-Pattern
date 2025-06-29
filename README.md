# 🐾 Pet Adoption System

The **Pet Adoption System** is a user-friendly platform that enables users to adopt or give pets up for adoption with the help of an admin panel. Built to simplify and streamline the pet adoption process, the system helps connect pets with loving homes through a centralized web interface.

---

## 📌 Project Overview

Users who wish to give away their pets can submit a form, which is reviewed by the admin. Once approved, the pet gets listed on the site. People interested in adopting can browse the listed pets, submit adoption requests, and if selected by the admin, will receive the adoption details. The admin handles approvals, removals, and records of past adoptions.

---

## ✨ Features

- 📝 Submit pet details for adoption
- 🔎 Search and filter pets by type (dog, cat, etc.)
- 🖼️ View detailed profiles of each pet
- 📋 Adoption form for users
- ✅ Admin panel to approve or reject submissions
- ❌ Auto-deletion of unapproved requests once a pet is adopted
- 📦 Record management of previous adoptions

---

## 🛠️ Tech Stack

- **MongoDB** – Database for storing users, pets, and adoption info
- **Express.js** – Backend framework
- **React.js** – Frontend user interface
- **Node.js** – JavaScript runtime for the backend

---

## ⚙️ Installation & Setup

Follow the steps below to run this project on your local machine:

### 1. Clone the Repository
git clone https://github.com/yourusername/Pet-Adoption-System.git
cd Pet-Adoption-System

2. Install Dependencies
npm install

3. Configure Environment Variables
Create a .env file inside the server folder and add your MongoDB connection string:
mongooseURL=mongodb://username:password@host:port/database_name

4. Start the Development Server
Backend
nodemon server

Frontend
npm start
