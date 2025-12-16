# 🌐 G-Blogs: The Social Travel Ecosystem

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-5.0-092E20?style=for-the-badge&logo=django&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3%20%2F%20JS-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production--Grade-success?style=for-the-badge)

> **"The Future of Social Travel is Just a Click Away."**

---

## 🔥 Introduction

**G-Blogs** is not just another social media clone; it is a sophisticated, full-stack web application engineered for travelers and storytellers. It bridges the gap between the instant gratification of **Instagram** and the structured networking of **LinkedIn**.

From real-time interactions without page reloads to a complex **Visa Journey tracking system**, every feature has been hand-coded to provide a seamless, **"FAANG-level"** user experience.

---

## 💎 Core Experience

### 🔍 The "Explore" Engine
A reimagined search experience that feels instant and fluid.
* **Zero-Latency Search:** As you type, results for both *People* and *Posts* appear instantly via AJAX with no page reloads.
* **Smart Discovery:** When the search bar is empty, an intelligent "Explore Grid" showcases trending content in a responsive mosaic layout.
* **Visual Polish:** Featuring a glassmorphism search bar and hover-reveal user cards.

### 📱 Immersive Social Feed
* **Split-Screen Detail View:** Clicking a post opens a "Theater Mode" — media on the left, scrolling conversation on the right.
* **Instant Engagement:** Like and Comment actions happen in real-time.
* **Rich Media Support:** Seamless handling of high-res images and auto-playing videos.

### ✈️ The Visa Journey System (Unique Feature)
A specialized feature exclusively for global travelers.
* **Digital Passport:** Users can select visas they have earned from a master database.
* **Storytelling:** Each selected visa opens a dedicated *Journey Modal*, allowing the user to share the specific story of how they obtained it.
* **Visual Logic:** Selected visas appear as a horizontal scrolling showcase on the profile with status indicators.

### 🔐 Fortified Identity System
* **Custom Auth:** Email-first login system replacing legacy usernames.
* **Security:** Integrated SMTP email verification and secure password recovery flows.
* **One-Click Onboarding:** Google OAuth2 social login integration.

---

## 🛠️ Technical Architecture

The engineering behind G-Blogs is robust and scalable.

| Layer | Technology |
| :--- | :--- |
| **Backend** | Django 5.2 (Python 3.12) |
| **Database** | SQLite (Dev) / PostgreSQL (Prod-Ready) |
| **Frontend** | HTML5, Advanced CSS3 (Variables, Grid), Vanilla JS (ES6+) |
| **Async Tasks** | AJAX / Fetch API for non-blocking UI updates |
| **Media** | Pillow for image processing & optimization |
| **Hosting** | Deployed on PythonAnywhere |

---

## 📸 Feature Highlights

* **Responsive 3-Column Layout:** A "Holy Grail" layout with a sticky Navbar, infinite scrolling Feed, and dynamic Suggestions sidebar.
* **Smart Suggestions:** A sidebar algorithm that recommends users to follow based on network logic.
* **Profile Customization:** Full control over bio, profile picture, and visa showcase visibility.

---

## 🚀 How to Run Locally

Want to explore the code? Follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/PythonicPete/G-Blogs.git](https://github.com/PythonicPete/G-Blogs.git)
    cd G-Blogs
    ```

2.  **Create a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run Migrations**
    ```bash
    python manage.py migrate
    ```

5.  **Start the Server**
    ```bash
    python manage.py runserver
    ```

---

## ✨ Experience G-Blogs Live

Visit the live site to experience these interactive features firsthand.

[**👉 Launch G-Blogs Live**](http://your-username.pythonanywhere.com)

---

### 👨‍💻 Author

**Designed & Developed by Gourav**
*Passionate about building production-grade software with Django.*
