# 🧭 Sidebar Demo Project

A modern **Sidebar Navigation UI** built with **HTML, CSS, and JavaScript**.
Features a **collapsible side menu**, smooth width transition, and interactive hover effects.

🔗 **[Live Demo](https://nsnet21.github.io/04-sidebar/)**

---

## 🖼️ Preview

![Sidebar Preview](assets-preview/preview.jpeg)

---

## 🚀 Features

- 🧩 **Collapsible Sidebar** — toggle sidebar width with animation.
- 🎨 **Smooth Transition Effects** — width, opacity, and text reveal animations.
- 💡 **Hover Highlights** — glowing accent hover effects on icons and logo.
- 🧱 **Organized Layout** — header, menu, and footer separated clearly.
- 🧰 **Lightweight** — written with pure HTML, CSS, and vanilla JavaScript.
- 🖋️ **Google Fonts & Boxicons** — clean typography and modern icon set.

---

## 🧠 How It Works

- The sidebar is controlled by a JS event listener:

  ```js
  toggleBtn.addEventListener("click", () => {
    sideNavBar.classList.toggle("collapsed");
  });
  ```

- When .collapsed is active:

  ```
  - Sidebar width shrinks from 220px → 68px.
  - Text fades out and hides.
  - Only icons remain visible.
  ```

## 🧾 File Structure

```
04Sidebar/
│
├── assets-preview/
│   └── preview.jpeg
│
├── images/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🧱 Tech Stack

- HTML5 — semantic structure

- CSS3 — transitions, variables, hover effects

- JavaScript (ES6) — DOM manipulation

- Boxicons & Google Fonts — design enhancement

## ✨ Font & Icon Libraries

- Google Fonts:

  > • Poppins <br>
  > • Noto Serif JP

- Boxicons: https://boxicons.com

- Font Awesome (CDN): https://cdnjs.com/libraries/font-awesome
