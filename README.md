# Urban Sole — Online Store 👟

A front-end web project for **Urban Sole**, an online shoe store. The site lets users browse a catalog of shoes, add items to a cart with live quantity and subtotal updates, and learn about the brand.

> ⚠️ **Work in progress** — this project is being built and uploaded in stages. Expect new features, fixes, and pages to land over the coming days.

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
URBAN SOLE ONLINE STORE/
├── HTML/
│   ├── index.html          # Home page
│   ├── product1.html       # Product listing + cart
│   ├── About.html          # About us
│   ├── Contact.html        # Contact form
│   ├── app.js              # Cart logic (add/remove/update)
│   ├── product.js          # Product data
│   ├── style.css           # Main styles
│   ├── style1.css          # Product/cart styles
│   ├── image/              # Shoe product images
│   ├── images/             # Banners & media
│   └── icons/              # UI icons
│
└── docs/                   # Supporting project documents
    ├── Sales of the year FINAL.xlsx
    ├── weekly summary FINAL.xlsx
    ├── sheos data.accdb     # MS Access database
    ├── flowchrt.vsdx        # Visio flowchart
    ├── Informational brochure.pub
    ├── urban sole visiting card.pub
    └── Logo / flyer / screenshots

