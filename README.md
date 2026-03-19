# 🌐 Personal Portfolio Website

![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-00dcc8?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-f0c060?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-ff4d6d?style=for-the-badge)

A fully responsive, single-file personal portfolio website built with pure **HTML5, CSS3, and Vanilla JavaScript** — no frameworks, no build tools, no dependencies.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 |
| Scripting | Vanilla JavaScript |
| Fonts | Google Fonts (via CDN) |
| Background Effect | HTML5 Canvas API |

---

## 📁 File Structure

```
portfolio/
│
├── sharath_portfolio.html    # Single-file portfolio (HTML + CSS + JS combined)
└── README.md                 # This file
```

---

## ⚙️ CSS Features Used

- **CSS Custom Properties** (variables) for consistent theming
- **CSS Grid & Flexbox** for layout
- **CSS Keyframe Animations** for entrance effects and looping animations
- **CSS Transitions** for hover states and micro-interactions
- **`backdrop-filter`** for frosted glass nav blur effect
- **`-webkit-text-stroke`** for outlined display text
- **`:has()` selector** for cursor state changes on hover
- **`::-webkit-scrollbar`** for custom styled scrollbar
- **`clamp()`** for fluid responsive typography
- **`mix-blend-mode: screen`** on the custom cursor dot
- **CSS `@media` queries** for mobile responsiveness

---

## ⚡ JavaScript Features Used

- **HTML5 Canvas API** — Particle system with 120 animated nodes and dynamic connection lines drawn each frame via `requestAnimationFrame`
- **Intersection Observer API** — Scroll-triggered reveal animations and skill bar fills
- **`mousemove` event listener** — Custom cursor tracking
- **`scroll` event listener** — Active nav link highlighting based on scroll position
- **Prototypal OOP** — `Particle` constructor function with `reset`, `update`, and `draw` methods
- **No jQuery, no libraries** — Pure ES5-compatible vanilla JS throughout

---

## 🎨 Design System

### Color Palette
| Name | Hex | Usage |
|------|-----|-------|
| Background | `#050810` | Page base |
| Surface | `#0d1424` | Cards, code block |
| Cyan | `#00dcc8` | Primary accent, highlights |
| Gold | `#f0c060` | Secondary accent |
| Red | `#ff4d6d` | Tertiary accent |
| Muted | `#5a6882` | Body text, labels |

### Typography
| Font | Style | Usage |
|------|-------|-------|
| `Syne` | 700–800 weight | Headings, nav logo |
| `JetBrains Mono` | 300–700 weight | Body, code, labels |
| `Playfair Display` | Italic | Decorative accent text |

---

## ✨ UI Components

- **Animated particle network** — Canvas-based floating nodes with proximity connection lines
- **Custom cursor** — Dot + ring cursor that morphs on link hover using `:has()`
- **Hero code block** — Syntax-highlighted fake Python snippet with a blinking type cursor
- **Skill bars** — Animated progress bars triggered by Intersection Observer
- **Project cards** — Hover lift effect with gradient overlay
- **Education timeline** — Vertical line with glowing dot indicator
- **Scroll reveal** — All sections fade up into view on scroll
- **Active nav** — Navigation links highlight based on current scroll section
- **Gmail compose redirect** — Email buttons open Gmail in a new tab with `To` pre-filled using query params (`?view=cm&to=...`)

---

## 🚀 How to Run

No installation or build step required:

```bash
# macOS
open sharath_portfolio.html

# Windows
start sharath_portfolio.html

# Linux
xdg-open sharath_portfolio.html
```

Or simply drag and drop `sharath_portfolio.html` into any browser.

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
