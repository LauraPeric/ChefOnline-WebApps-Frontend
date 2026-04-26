# 👨‍🍳 ChefOnline 👩‍🍳 (Frontend)

ChefOnline is a modern web application designed for cooking enthusiasts of all skill levels. It provides a platform where users can discover recipes, share their own culinary creations, participate in forum discussions, and interact with other users through comments and ratings.

The application is built as a **single-page application (SPA)** using Vue.js and communicates with a backend API and Firebase services for authentication and data management.

---

## 🚀 Live Demo

🔗 https://projekt-web-apps-frontend.vercel.app/

---

## 🧠 Project Overview

ChefOnline is a community-driven cooking platform that enables users to:

- Browse and search recipes
- View detailed recipe pages
- Create and share posts
- Participate in forum discussions
- Comment and interact with other users
- Save favorite recipes
- Manage user profiles and authentication

The goal of the application is to create an interactive and engaging culinary community platform.

---

## 🛠 Tech Stack

- **Frontend Framework:** Vue.js 3
- **Routing:** Vue Router
- **State Management:** Vuex
- **HTTP Client:** Axios
- **Backend Integration:** REST API
- **Authentication & Database:** Firebase
- **UI Styling:** Bootstrap 5 + custom SCSS
- **Email Service:** EmailJS
- **Deployment:** Vercel

---

## 📁 Project Structure

The application follows a modular Vue architecture:

- **/views** → Application pages (Home, Recipes, Forum, Profile, etc.)
- **/components** → Reusable UI components (navbar, cards, forms)
- **/router** → Route definitions and navigation
- **/services** → API calls and backend communication logic
- **/store** → Vuex state management
- **firebase.js** → Firebase configuration and initialization

---

## 🔐 Authentication

- Firebase Authentication is used for user login and registration
- User sessions are managed via authentication tokens
- Protected routes are handled through Vue Router logic

---

## 🌐 Routing

The application includes multiple routes such as:

- `/` – Home page
- `/recepti` – Recipes listing
- `/forum` – Community forum
- `/onama` – About page
- `/info` – Information page
- `/samiprofil` – User profile
- `/login`, `/signup` – Authentication pages

Dynamic views are used for recipe and forum detail pages.

---

## 🎯 Features

- 🍽 Recipe browsing and filtering
- 🧑‍🍳 Recipe creation and sharing
- 💬 Forum discussions between users
- ⭐ Save favorite recipes
- 🔐 Firebase authentication system
- 📱 Responsive UI design
- 📤 PDF export and content sharing tools
- 📧 Email integration via EmailJS

---

## 🔥 Key Technical Highlights

- Vue.js SPA architecture with component-based design
- Firebase integration for authentication and data handling
- REST API communication via Axios
- Vuex state management for global app state
- Modular service layer for backend calls
- Responsive Bootstrap + SCSS styling system
- Deployed on Vercel with CI/CD workflow

---

## 📌 Project Context

This project was developed as part of the **Web Applications course** at the Faculty of Informatics, Juraj Dobrila University of Pula during the academic year 2023/2024.

---

## 👨‍💻 Author

**Laura Perić**  
Full design and implementation of the application
