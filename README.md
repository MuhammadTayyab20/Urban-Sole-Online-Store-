# Urban Sole — Online Store 👟

A front-end web project for **Urban Sole**, an online shoe store. The site lets users browse a catalog of shoes, add items to a cart with live quantity and subtotal updates, and learn about the brand.

---

## 🛍️ Features

- **Home page** with an auto-playing banner slideshow, free-shipping and customer-support highlights, and a featured-products section.
- **Product page** that dynamically renders the shoe catalog from JavaScript data.
- **Shopping cart** built in vanilla JS:
  - Add items to cart
  - Increase / decrease quantity (respecting available stock)
  - Remove items
  - Live subtotal and total-item count
  - Cart persists across page reloads using `localStorage`
- **About Us** page describing the brand story.
- **Contact Us** page with a contact form.
- Responsive layout styled with custom CSS.

---

## 🧰 Tech Stack

- **HTML5** — page structure
- **CSS3** — styling (`style.css`, `style1.css`)
- **JavaScript (Vanilla)** — product rendering and cart logic (`app.js`, `product.js`)
- **Font Awesome** & **Bootstrap Icons** — UI icons
- **localStorage** — client-side cart persistence

---

## 📁 Project Structure

```
Urban-Sole-Online-Store-/
├── HTML/                          # The website
│   ├── index.html                 # Home page
│   ├── product1.html              # Product listing + cart
│   ├── About.html                 # About us
│   ├── Contact.html               # Contact form
│   ├── app.js                     # Cart logic (add/remove/update)
│   ├── product.js                 # Product data
│   ├── style.css                  # Main styles
│   ├── style1.css                 # Product/cart styles
│   ├── image/                     # Shoe product images
│   ├── images/                    # Banners & media
│   └── icons/                     # UI icons
│
├── Logo.png                       # Brand logo
├── Sales of the year FINAL.xlsx   # Sales data
├── sheos data.accdb               # MS Access database
├── Informational brochure.pub     # Brand brochure
└── urban sole visiting card.pub   # Visiting card design
```

---

## ▶️ Getting Started

It's a static site — no build tools needed.

1. Clone or download the repo.
2. Open the `HTML` folder.
3. Open `index.html` in your browser.

To run a local server (recommended so images and links resolve cleanly):

```bash
cd HTML
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## 🗺️ Roadmap

- [ ] Fix internal page links and file references
- [ ] Wire up the contact form to a working backend
- [ ] Replace placeholder product descriptions with real copy
- [ ] Add a dedicated cart/checkout page
- [ ] Make the layout fully responsive for mobile
- [ ] Switch prices to PKR (Rs.)

---
