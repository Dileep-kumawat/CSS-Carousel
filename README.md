## 📌 CSS-Carousel

A **pure CSS carousel** - no JavaScript, dependency-free, lightweight, and easy to integrate.

- 🔗 **Live Demo:** [https://dileep-kumawat.github.io/CSS-Carousel/](https://dileep-kumawat.github.io/CSS-Carousel/)
- 📂 **GitHub Repo:** [https://github.com/Dileep-kumawat/CSS-Carousel.git](https://github.com/Dileep-kumawat/CSS-Carousel.git)

---

## 🔍 Overview

This project is a CSS-only carousel component that lets you slide through images or content cards without any JavaScript. It uses modern CSS techniques (like `:checked` states and transitions) to deliver smooth behavior with minimal code.

If your goal was “carousel without JS” - mission accomplished. But be honest: CSS-only carousels have limitations (accessibility, keyboard controls, swipe support). You should eventually pair this with JS if you want a production-grade component.

---

## 🚀 Features

- ✔ No JavaScript required
- ✔ Simple and clean markup
- ✔ Smooth transitions
- ✔ Easy to customize (sizes, colors, animation timing)
- ✔ Ideal for static pages or minimal UI needs

---

## 📦 Demo

Open the live demo in a browser to see it in action:

👉 [https://dileep-kumawat.github.io/CSS-Carousel/](https://dileep-kumawat.github.io/CSS-Carousel/)

---

## 🧠 How It Works

This carousel uses:

* Radio inputs to track the active slide
* Labels as navigation controls (next/prev)
* CSS sibling selectors for state changes
* CSS transitions for smooth slide animation

It’s clever, but it’s not a complete replacement for JS equivalents - no swipe support, no dynamic slide injection, limited accessibility.

---

## 📁 How to Use

### 1. Clone the repo

```bash
git clone https://github.com/Dileep-kumawat/CSS-Carousel.git
cd CSS-Carousel
```

### 2. Open in Browser

You can open `index.html` directly or serve with a static server.

Example (with VS Code Live Server):

1. Install Live Server extension
2. Click **“Go Live”**
3. View carousel

### 3. Customize

Update images or content:

```html
<div class="carousel-slide">
  <img src="your-image.jpg" alt="Slide description">
</div>
```

Modify CSS variables:

```css
:root {
  --carousel-width: 800px;
  --carousel-height: 400px;
  --transition-time: 0.6s;
}
```

---

## 🛠️ Folder Structure

```
CSS-Carousel/
├─ index.html          # main demo page
├─ css/
│  └─ styles.css       # carousel styles
└─ assets/
   └─ images/          # sample images
```

---

## ⚙️ Customization Tips

**Navigation Buttons**
You can style next/prev arrows to fit your design:

```css
.carousel-nav label {
  background: rgba(0,0,0,0.4);
  color: #fff;
  padding: 8px 12px;
  border-radius: 4px;
}
```

**Responsive Breakpoints**
Add breakpoints for mobile:

```css
@media (max-width: 600px) {
  .carousel {
    width: 100%;
    height: auto;
  }
}
```

---

## 🤝 Contributing

Want to improve it? Great - open issues or PRs!

Just follow standard guidelines:

1. Fork the repository
2. Create a feature branch
3. Add tests/documentation
4. Submit a pull request

---

## 📜 License

MIT License - use it freely, improve it, share it.

---

# 📧 Contact

👤 **Dileep kumawat**
- 📧 [dileepkumawat525@gmail.com](mailto:dileepkumawat525@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/dileep-kumawat/)

---
