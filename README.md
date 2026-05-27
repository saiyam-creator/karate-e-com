<div align="center">

# ⚡ KRATE — The Ultimate Shop

### A cinematic scroll-driven e-commerce experience built from scratch with pure HTML, CSS & JavaScript.

[![Live Demo](https://img.shields.io/badge/🔴_LIVE_DEMO-Visit_Site-e8381c?style=for-the-badge)](https://saiyam-creator.github.io/3d-enhenced-portfolio/)
[![Made With Love](https://img.shields.io/badge/Made_with-❤️_&_JS-black?style=for-the-badge)](#)
[![No Framework](https://img.shields.io/badge/Zero_Framework-Pure_HTML/CSS/JS-white?style=for-the-badge)](#)

<br/>

![KRATE Banner](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=1200&q=80)

</div>

---

## 🎬 What is KRATE?

**KRATE** is a fully animated, scroll-driven e-commerce concept website — built entirely with **vanilla HTML, CSS, and JavaScript**. No React. No Vue. No template. Just raw code and cinematic motion.

Scroll through 3 assembling rings, zoom past them into a product showcase, browse featured drops, and check out with a multi-step flow — all in one single HTML file.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔵 **Cinematic Ring Tunnel** | 3 rings assemble from broken pieces as you scroll, each zooming past the camera |
| 📝 **Scroll-Triggered Side Text** | Bold text fades in left & right when each ring is broken, disappears when it joins |
| 🎞️ **GSAP ScrollTrigger** | Smooth, scrub-based scroll animations throughout |
| 🖱️ **Custom Cursor** | Red dot + ring cursor with hover & drag states |
| 🌟 **Cinematic Loader** | Panel wipe reveal with animated progress bar |
| 🃏 **Featured Card Slider** | Horizontal scroll-driven product card slideshow |
| 🛒 **Full Cart System** | Add, remove, quantity control, subtotal, delivery calc |
| 💳 **3-Step Checkout Modal** | Address → Payment → Review flow |
| 🔥 **Firebase Auth** | Google login + email/password authentication |
| 📱 **Product Showcase** | Ring scene ends with arrow-navigable product cards |
| 🎨 **Motion UI** | Parallax, particles, marquee strip, burst flash, glow effects |
| 📦 **All Products Page** | Full catalogue with category filters |
| ⚡ **SaiTech Badge** | Branded side badge linking to the creator's portfolio |

---

## 🛠️ Tech Stack

```
HTML5          →  Structure & layout
CSS3           →  Animations, variables, sticky scenes, grid/flex
JavaScript     →  Scroll engine, cart, auth, canvas drawing
GSAP 3         →  ScrollTrigger, tweens, stagger animations
Canvas API     →  Ring drawing, arc animation, circular text
Firebase       →  Auth (Google + Email/Password), Firestore
Google Fonts   →  Bebas Neue + Epilogue
```

---

## 🚀 Getting Started

No build step. No npm install. Just open and run.

```bash
# Clone the repo
git clone https://github.com/your-username/krate.git

# Open in browser
open ind.html
```

Or just visit the **[Live Demo →](https://saiyam-creator.github.io/3d-enhenced-portfolio/)**

---

## 🗂️ Project Structure

```
krate/
│
├── ind.html          # Entire site — HTML + CSS + JS in one file
└── README.md         # This file
```

> The whole site lives in a **single HTML file** — every style, animation, and script is self-contained.

---

## 🎮 How the Scroll Experience Works

```
Page Load
   ↓
🎬 Cinematic Loader  (panel wipe reveal)
   ↓
🦸 Hero Section      (parallax + word reveal)
   ↓
💍 Ring 1 — Outer    (broken → assembles → zooms past)
   ↓  ← side text fades in/out here
💍 Ring 2 — Middle   (same flow, different timing)
   ↓
💍 Ring 3 — Inner    (fastest zoom, burst flash)
   ↓
🛍️ Product Showcase  (arrow-navigable cards appear)
   ↓
📦 Featured Drops    (horizontal scroll cards)
   ↓
📖 How It Works      (4-step cinematic walkthrough)
   ↓
🔖 Deals + Reviews + Footer
```

---

## ➕ Adding a New Product

Open `ind.html`, find the `PRODS` array (search for `PRODUCTS CONFIG`), and add a new block:

```js
{
  id: 13,                              // unique number
  nm: 'Your Product Name',
  price: 999,
  old: 1499,                           // cut price — delete this line if not needed
  img: 'https://your-image-url.jpg',   // any direct image URL
  cat: 'tech',                         // tech | fashion | home | fitness | beauty
  badge: 'NEW', nw: true,              // delete this line for no badge
  desc: 'Short product description'
},
```

That's it — the product appears everywhere automatically (featured slider, ring showcase, all products page).

---

## 👤 About

Built by **[Saiyam](https://saiyam-creator.github.io/3d-enhenced-portfolio/)** — a first scroll-driven, motion-controlled UI project.

> *"This is what happens when curiosity meets a blank HTML file."*

<div align="center">

**⚡ A [SaiTech](https://saiyam-creator.github.io/3d-enhenced-portfolio/) Project**

</div>
