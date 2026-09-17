

# 👨‍💻 Dhiraj Kumar | Personal Portfolio

![Portfolio Preview](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

A premium, high-performance personal portfolio website designed with a **modern Apple-inspired dark aesthetic**. This project showcases my skills, experience, and projects using clean code, "glassmorphism" UI effects, and a fully responsive layout.

---

## ✨ Features

* **🎨 Premium UI/UX:** Dark mode aesthetic with glass-morphism cards, subtle gradients, and smooth transitions.
* **📱 Fully Responsive:** Optimized for all devices, from large desktop screens to mobile phones.
* **⚡ High Performance:** Built with pure HTML5, CSS3, and Vanilla JavaScript (No heavy frameworks).
* **📧 Working Contact Form:** Integrated with **Formspree** for server-less email handling.
* **🗺️ Interactive Map:** Embedded dark-mode Google Map for location visualization.
* **🔄 Dynamic Content:** JavaScript-powered experience timeline that automatically calculates employment duration.
* **📁 Modular CSS:** Organized stylesheet architecture (`styles.css`, `projectcss.css`, `contactcss.css`) for easy maintenance.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Variables, Flexbox/Grid), JavaScript (ES6+)
* **Icons:** FontAwesome 6.4.0
* **Fonts:** Inter (Google Fonts)
* **Form Handling:** Formspree (AJAX submission)

---

## 📂 Project Structure

```text
/
├── index.html          # Landing Page (Hero Section)
├── about.html          # Skills & Bio
├── project.html        # Project Showcase
├── experience.html     # Professional Timeline
├── contact.html        # Contact Form & Socials
├── styles.css          # Global Variables & Core Styles
├── projectcss.css      # Specific Styles for Project Grid
├── experience.css      # Specific Styles for Timeline
├── contactcss.css      # Specific Styles for Contact Layout
├── script.js           # Mobile Menu Logic & Global Scripts
└── README.md           # Documentation


## 🚀 How to Run Locally

1. **Clone the repository:**
```bash
git clone [https://github.com/dhiraj7kr/portfolio-website.git](https://github.com/dhiraj7kr/digitalDhiraj.git)
cd portfolio-website

```


2. **Open in VS Code:**
```bash
code .

```


3. **Run with Live Server:**
* Install the "Live Server" extension in VS Code.
* Right-click `index.html` and select **"Open with Live Server"**.



---

## ⚙️ Configuration

### 1. Contact Form (Formspree)

To make the contact form send emails to your inbox:

1. Go to [Formspree](https://formspree.io/) and create a new form.
2. Copy your unique **Form Endpoint** (e.g., `https://formspree.io/f/xvng...`).
3. Open `contact.html` and replace the action URL:
```html
<form id="contact-form" action="YOUR_FORMSPREE_URL_HERE" method="POST">

```



### 2. Google Maps

To update the location map:

1. Go to Google Maps and search for your location.
2. Click **Share** > **Embed a map**.
3. Copy the `<iframe>` code.
4. Paste it into the `.map-container` div in `contact.html`.
5. *Optional:* Add `filter: grayscale(100%) invert(92%) contrast(83%);` in CSS for the dark mode look.

---

## 📬 Contact

* **Email:** [dhiraj7kr@gmail.com](mailto:dhiraj7kr@gmail.com)
* **LinkedIn:** [linkedin.com/in/dhiraj7kr](https://linkedin.com/in/dhiraj7kr)
* **GitHub:** [github.com/dhiraj7kr](https://github.com/dhiraj7kr)

---

© 2026 Dhiraj Kumar. All Rights Reserved.

```

```
