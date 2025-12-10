# 🎓 College Dating App

> **Purpose:** This app is built exclusively for college usage to help students connect, interact, and meet new people in a safe, verified digital environment.

A simple, clean, and functional dating web application designed specifically for university campuses.

---

## 🚀 Features & Components

### 1. 🔐 Auth System
Secure access to ensure only verified students connect.
* **Signup Page:** Registration using Email or distinct College ID.
* **Login Page:** Standard Email + Password authentication.
* **Forgot Password:** Basic password reset functionality via email.

### 2. 👤 User Profiles
Comprehensive profiles to help students showcase their personalities.
* **Profile Picture:** Image upload functionality.
* **Basic Details:** Name, Age, Course/Major, Year of Study.
* **Bio:** Short "About Me" section.
* **Interests:** Selectable tags (Music, Sports, Books, Coding, etc.).
* **Edit Profile:** Ability to update details later.

### 3. ❤️ Matching System
Multiple ways to find a connection.
* **Swipe-based Matching:** Tinder-style Like/Dislike cards.
* **Interest-based:** Recommendations based on common hobbies.
* **Academic Filtering:** Filter by Department or Year.

### 4. 💬 Chat System
* **Real-time Messaging:** Powered by Socket.io (or polling).
* **Match List:** Dedicated page showing all successful matches.
* **Features:** Text messages, emojis, and timestamps.

### 5. 🔍 Search & Filters
* **Filters:** Narrow down by Year, Department, Age, or Interests.
* **Direct Search:** Find specific users by name.

### 6. 🌍 Feed / Explore Page
A dashboard to discover new people.
* **Card View:** Displays Image, Name, Age, and Bio.
* **Action:** "Like" button on cards.

### 7. 🛡️ Safety Features
* **Report User:** Flag inappropriate behavior.
* **Block User:** Prevent specific users from contacting you.
* **Domain Restriction:** (Optional) Restrict signups to college email domains only (e.g., `@university.edu`).

### 8. ⚙️ Admin Panel (Optional)
* User Verification/Approval.
* Moderation (Remove inappropriate profiles).
* User Statistics dashboard.

---

## 🛠️ Tech Stack

| Component | Technologies |
| :--- | :--- |
| **Frontend** | HTML/CSS, EJS, React, TailwindCSS |
| **Backend** | Node.js + Express |
| **Database** | MongoDB or PostgreSQL |
| **Real-time** | Socket.io |
| **Auth** | JWT (JSON Web Tokens) or Passport.js |



[Image of simple web application architecture diagram]


---

## 📂 Folder Structure

```text
project/
│
├── public/              # Static files
│   ├── images/
│   ├── css/
│   └── js/
│
├── src/                 # Source code
│   ├── routes/          # API routes
│   ├── controllers/     # Logic for routes
│   ├── models/          # Database schemas
│   └── views/           # EJS templates or React components
│
├── app.js               # Entry point
├── package.json         # Dependencies
└── README.md            # Documentation