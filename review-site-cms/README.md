# 🎬 Review Site (Strapi + Vue 3)

## 📌 Project Overview

This project is a **dynamic Review Website** built using a **Headless CMS (Strapi)** and a **Vue 3 frontend framework**.  
It allows users to browse, search, and view detailed reviews for different types of media such as **video games and movies**.

The backend (Strapi CMS) provides a REST API, which is consumed by the Vue frontend to display dynamic content.

---


## 🧑‍💻 Developer

- Prayash Kharel

---

## 🛠️ Technologies Used

### Backend (Headless CMS)
- Strapi (Node.js Headless CMS)
- REST API
- SQLite Database (default)

### Frontend
- Vue 3 (Composition API)
- Vue Router
- Axios (API calls)
- HTML5, CSS3
- Responsive Web Design

---

## 🎯 Features

### 📡 Backend (Strapi CMS)
- Custom content type: **Review**
- Fields included:
  - Title
  - Slug
  - Description
  - Content (Rich Text)
  - Rating (Number)
  - Image (optional)
- REST API enabled
- Public API permissions configured for read access

---

### 💻 Frontend (Vue Application)

- 📄 Displays a list of reviews (minimum 10 reviews)
- 🔍 Search functionality (filter reviews by title)
- 🖱️ Clickable review cards
- 📖 Dynamic review detail page
- 🧭 Site-wide navigation bar
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎨 Modern dark-themed UI design

---

## 🔗 API Endpoints

### Get all reviews:
```txt
GET http://localhost:1337/api/reviews?populate=*