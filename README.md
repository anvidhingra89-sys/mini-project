<div align="center">

# 🍽️ The Food Atelier

### *Where Every Bite Is A Masterpiece*

A clean, elegant, and fully responsive restaurant website — built with pure **HTML** and **CSS**.
No frameworks. No dependencies. Just great food, beautifully presented.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)

[✨ Features](#-features) · [🍕 Menu](#-the-menu) · [🚀 Getting Started](#-getting-started) · [📁 Structure](#-project-structure) · [🎨 Customize](#-customization) · [🗺️ Roadmap](#%EF%B8%8F-roadmap)

</div>

---

## 📖 About

**The Food Atelier** is a single-page restaurant website designed to showcase a menu, tell the restaurant's story, and make it easy for guests to get in touch. It's lightweight, loads instantly, and works on every device — from phones to widescreen desktops.

Every dish on the menu has an **interactive ingredients dropdown**, so guests can see exactly what goes into their meal — all without a single line of JavaScript.

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🎯 | **Hero Section** | A bold tagline with a call-to-action button that jumps straight to the menu |
| 🍴 | **Interactive Menu Cards** | Six dishes with photos, prices (₹) and expandable ingredient lists |
| 🧭 | **Smooth In-Page Navigation** | Header links jump to Home, Menu, About and Contact sections |
| 📱 | **Responsive Design** | Built with the viewport meta tag and a mobile-friendly layout |
| ⚡ | **Zero JavaScript** | Ingredient toggles use the native HTML `<details>` element |
| ♿ | **Accessible Markup** | Semantic tags (`header`, `section`, `nav`, `footer`) and descriptive `alt` text |
| 📞 | **Contact Section** | Address, phone and email displayed in clean info cards |
| 🪶 | **Featherweight** | Just one HTML file and one stylesheet — nothing to install or build |

---

## 🍕 The Menu

| Dish | Price | Highlights |
|---|:---:|---|
| 🍕 **Italian Pizza** | ₹249 | Mozzarella, fresh basil, cherry tomatoes, olive oil |
| 🍝 **Creamy Pasta** | ₹199 | White sauce, cheese, garlic, capsicum, Italian herbs |
| 🍔 **Cheese Burger** | ₹179 | Veggie patty, cheese, lettuce, tomato, onion |
| 🥪 **Grilled Sandwich** | ₹149 | Cheese, capsicum, tomato, onion, butter |
| 🍛 **Classic North Indian Thali** | ₹399 | Dal Makhani, Shahi Paneer, Jeera Rice, Butter Naan, Gulab Jamun |
| 🍰 **Tiramisu** | ₹249 | Ladyfingers, mascarpone, coffee, cocoa |

---

## 🚀 Getting Started

No build tools, no package managers — just open and go.

### Option 1 — Open directly

```bash
# Clone the repository
git clone https://github.com/<your-username>/the-food-atelier.git

# Move into the project folder
cd the-food-atelier

# Open index.html in your browser
```

Then double-click **`index.html`**, or run:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Option 2 — Run a local server

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Visit **http://localhost:8000** in your browser.

### Option 3 — Deploy for free with GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and the `/ (root)` folder
4. Click **Save** — your site will be live at `https://<your-username>.github.io/the-food-atelier/`

---

## 📁 Project Structure

```
the-food-atelier/
│
├── index.html          # Main page: hero, menu, about, contact
├── style.css           # All styling and layout
│
├── italian_pizza.jpg   # Menu images
├── cheese_pasta.jpeg
├── burger.jpg
├── sandwich.jpg
├── thali.jpg
├── tiramisu.jpg
│
└── README.md
```

---

## 🎨 Customization

### Add a new dish

Copy this block inside the `.menu-container` in `index.html`:

```html
<div class="food-card">
    <img src="your_dish.jpg" alt="Your Dish">
    <div class="food-info">
        <h3>Your Dish Name</h3>
        <p class="price">₹000</p>
        <details>
            <summary>Ingredients +</summary>
            <ul>
                <li>Ingredient one</li>
                <li>Ingredient two</li>
            </ul>
        </details>
    </div>
</div>
```

### Update restaurant details

Edit the **Contact Us** section at the bottom of `index.html` to change the address, phone number, and email.

### Change the look

All colours, fonts and spacing live in `style.css` — tweak them to match your brand.

---

## 🧱 Built With

- **HTML5**: semantic structure and the native `<details>` / `<summary>` disclosure widget
- **CSS3**: layout, styling and responsiveness

---

## 🗺️ Roadmap

- [ ] 🛒 Online ordering / cart
- [ ] 📅 Table reservation form
- [ ] 🌙 Dark mode toggle
- [ ] 🔎 Menu filters (veg, dessert, mains)
- [ ] 🖼️ Photo gallery section
- [ ] ⭐ Customer reviews
- [ ] 🗺️ Embedded Google Map in the contact section
-
