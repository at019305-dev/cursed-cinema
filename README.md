# 🕯️ The Cursed Realm

> A responsive horror-themed website built with pure HTML, CSS, and vanilla JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-fc036b)

---

## 📸 Preview

| Hero Section | Archives | Contact |
|---|---|---|
| Full-screen background with animated fade-in | 4-column horror card grid | Dark overlay call-to-action |

---

## ✨ Features

- **Mobile-first responsive design** — fluid layout from 320px to 4K
- **Accessible hamburger menu** — ARIA attributes, keyboard-friendly, closes on link click
- **Scroll-aware navbar** — frosted glass effect activates after 50px scroll
- **Horror card grid** — hover lift + glow effects with lazy-loaded images
- **CSS custom properties** — all colours and tokens in one place for easy theming
- **Smooth scroll & fade-in animations** — pure CSS, no library required
- **SEO-ready meta tags** — Open Graph tags included
- **Google Fonts** — Creepster (horror) + Oswald (body) loaded via `<link preconnect>`

---

## 🗂️ Project Structure

```
Task-3/
├── index.html        # Main HTML file
├── style.css         # All styles (mobile-first + media queries)
├── image/            # Project images
│   ├── images.png
│   └── WhatsApp Image *.jpeg (horror archive images)
└── README.md         # You are here
```

---

## 🚀 Getting Started

No build tools needed. Just open in a browser:

```bash
# Clone the repo
git clone https://github.com/at019305-dev/Task-3.git

# Open in browser
cd Task-3
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

Or simply drag `index.html` into any modern browser.

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `< 600px` | Single column cards, hamburger menu |
| `≥ 600px` | 2-column card grid |
| `≥ 1024px` | 4-column card grid, inline navbar |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure & accessibility |
| CSS3 | Styling, animations, CSS Grid, Flexbox |
| Vanilla JS | Hamburger toggle, scroll listener |
| Google Fonts | Creepster + Oswald typefaces |

---

## 🎨 Colour Palette

| Token | Hex | Usage |
|---|---|---|
| `--color-primary` | `#fc036b` | Accents, card titles, hover states |
| `--color-danger` | `#fc0303` | CTA buttons, divider lines |
| `--color-bg` | `#000000` | Page background |
| `--color-surface` | `rgba(0,0,0,0.85)` | Card backgrounds |

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 👤 Author

**at019305-dev**  
GitHub: [@at019305-dev](https://github.com/at019305-dev)

---

> *"Turn back before it learns your name."*
