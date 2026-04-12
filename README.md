# 🚀 Back2Belong – Campus Lost & Found Platform

Back2Belong is a real-time web application designed to help students and staff report, discover, and recover lost items efficiently within a campus environment.

🌐 **Live Demo:** https://back2belong.web.app/

---

## 📌 Problem Statement

In campuses, lost items like ID cards, laptops, keys, and bags are common. Traditional notice boards are inefficient, unorganized, and limited in reach.

---

## 💡 Solution

Back2Belong provides a centralized digital platform where users can:
- Report lost or found items
- Search and filter listings
- Communicate securely with other users
- Receive real-time updates and notifications

---

## ✨ Features

- 🔐 **User Authentication**
  - Email & Password login
  - Google Sign-In (OAuth)

- 📝 **Lost & Found Posts**
  - Add item details, category, location, and images
  - Edit, delete, or mark posts as resolved

- 🔍 **Advanced Search & Filters**
  - Filter by category, location, date, and keywords
  - Toggle between Lost / Found items

- 💬 **Real-Time Chat**
  - Direct messaging between users
  - Unread message tracking

- 🔔 **Notifications System**
  - In-app notifications for activity
  - Email alerts using EmailJS

- 📌 **Bookmarks**
  - Save and track important posts

- 🤖 **Smart Matching**
  - Automatically suggests matches between lost and found items

- 🌙 **Dark Mode**
  - Persistent theme preference

- 📱 **Responsive Design**
  - Optimized for mobile, tablet, and desktop

---
## 📸 Screenshots

### 🏠 Home Page
[Home](home.png)

### ➕ Add Item
[Add Item](add.png)

### 💬 Chat System(Contact)
[Chat](contact.png)

### 🔐 Sign in
[Sign-in](sign-in.png)

## 🛠️ Tech Stack

**Frontend:**
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)

**Backend & Services:**
- Firebase Authentication
- Cloud Firestore (NoSQL Database)
- Firebase Hosting
- Firebase Storage

**Third-Party Integrations:**
- Cloudinary (Image Hosting)
- EmailJS (Email Notifications)

---

## 🏗️ Architecture

- Single Page Application (SPA)
- Backend-as-a-Service using Firebase
- Real-time data updates with Firestore listeners

---

## 📂 Database Structure (Firestore)

- `posts` – Lost & found items  
- `bookmarks` – User saved posts  
- `notifications` – User alerts  
- `chats` – Chat metadata  
- `messages` – Chat messages  
- `reports` – Reported posts  
- `resolved` – Completed cases  

---

## 🚀 Key Learnings

- Building real-time applications using Firebase  
- Designing scalable NoSQL database structures  
- Implementing authentication and chat systems  
- Managing multiple features in a single-page application  
- Deploying and hosting production-ready apps  

---

## ⚡ Challenges Faced

- Designing a real-time chat system with unread tracking  
- Handling image uploads with fallback (Cloudinary → Firebase Storage)  
- Managing multiple features efficiently in a SPA architecture  

---

## 🔧 Setup 

- Clone the repository
- Open index.html and run in your browser
- Or simply visit the live demo:
  https://back2belong.web.app/

## 👩‍💻 Team

- Mansi Vaishya
- Riya Singh

## 📌 Note

This project was developed collaboratively, with a focus on building a real-time data-driven application using modern web technologies.
