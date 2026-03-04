# 🕌 Tour & Travels – Explore India 🌄

A beautifully designed **Tour & Travels Website** built using **HTML, CSS, Bootstrap, and JavaScript**.  
This website showcases India’s most iconic destinations, temples, valleys, and mountains — from the **Taj Mahal** to the **Kedarnath Temple**, and beyond.  
It provides an elegant user interface with **Dark Mode**, **Team Section**, **Interactive Navigation**, and **Smooth UI Transitions**.

---

## 🚀 Features

✅ **Fully Responsive Design** – Works seamlessly on desktops, tablets, and mobile devices.  
✅ **Modern UI/UX** – Clean layout, gradient navbar, hover animations, and section transitions.  
✅ **Dark/Light Mode Toggle** – Switch themes with one click (🌙 / ☀️).  
✅ **Explore India Section** – Includes 10+ famous Indian destinations with detailed descriptions and images.  
✅ **Founder & Team Section** – Highlights the founder and key team members with social media links.  
✅ **Integrated Navbar & Footer** – Navigation to all pages (Home, Destinations, Packages, Booking, About, Contact).  
✅ **Smooth Scroll & Transitions** – For a visually pleasing experience.  
✅ **SEO Optimized** – Includes meta descriptions and image alt tags.

---

## 📁 Folder Structure

Tour_travels/
│
├── index.html
├── about.html
├── booking.html
├── contact.html
├── destinations.html
├── packages.html
│
├── img/
│ ├── logo2.jpg
│ ├── taj.jpg
│ ├── kedarnath.jpg
│ ├── kashmir.jpg
│ ├── Meenakshi.jpg
│ ├── redfort.jpg
│ ├── mumbai.jpg
│ ├── goldentemple.jpg
│ ├── kerala.jpg
│ ├── kashi.jpg
│ ├── founder.jpg
│ ├── team2.jpg
│ └── team3.jpg
│
├── css/
│ └── style.css (optional external stylesheet)
│
├── js/
│ └── script.js (for dark mode or interactive behavior)
│
└── README.md


---

## 🧠 Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript (Vanilla)
- **Icons:** Font Awesome 6
- **Fonts:** Google Fonts (Poppins)
- **Responsive Design:** Bootstrap Grid System

---

## 💡 Pages Overview

| Page | Description |
|------|--------------|
| **index.html** | Homepage with introduction and navigation |
| **about.html** | Details about India’s heritage and top destinations |
| **booking.html** | Booking form for tour packages |
| **destinations.html** | Lists popular travel destinations |
| **packages.html** | Travel packages with pricing and offers |
| **contact.html** | Contact form for user inquiries |

---

## 🧭 Dark Mode Feature

This project includes a **Dark/Light Mode toggle button** in the navbar.  
Users can switch between themes instantly — perfect for better visibility at night or personal preference.

```javascript
const darkToggle = document.getElementById('darkToggle');
darkToggle.addEventListener('click', () => {
  document.body.classList.toggle('dark-mode');
  document.body.classList.toggle('light-mode');
  darkToggle.textContent = document.body.classList.contains('dark-mode') ? '☀' : '🌙';
});

## 👨‍💻 Author

Nitin Kumar
Junior Python Developer & Web Designer

📎 GitHub: Nitin765kumar

💼 LinkedIn: nitinkumar25

📸 Instagram: @Nitinkumar812719