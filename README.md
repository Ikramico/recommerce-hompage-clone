# Royal Stranger — Homepage Clone

A pixel-faithful front-end clone of the [Royal Stranger](https://royalstranger.com/) luxury furniture homepage, built with **pure HTML & raw CSS** — no frameworks, no libraries, no build tools.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📸 Preview

> Open `royal-stranger-clone.html` directly in any modern browser — no server required.

---

## 📁 Project Structure

```
royal-stranger-clone/
│
├── royal-stranger-clone.html   # Single self-contained file (HTML + CSS + JS)
└── README.md
```

> Everything lives in one file. Styles are in a `<style>` block in the `<head>`, and the small JS snippet is inline at the bottom of `<body>`.

---

## ✨ Sections Included

| Section | Description |
|---|---|
| **Header / Nav** | Fixed top bar with logo, menu toggle, and utility links |
| **Hero** | Full-viewport background image with headline and CTA |
| **Timeless Creations** | Intro text with explore link |
| **Category Grid** | 3-column grid — Seating, Lighting, Casegoods |
| **Featured Product** | Marshmallow Swivel Armchair two-column layout |
| **Julia Bar Table** | Full-bleed image with dark overlay panel |
| **Latest Project** | Asymmetric image grid with product callout |
| **About Strip** | Brand story split-panel section |
| **Testimonials** | Two-column client quotes |
| **The Crafted Edits** | Dark editorial section |
| **As Seen In** | Infinite marquee press strip |
| **Newsletter** | Email signup form |
| **Footer** | 4-column footer with links and legal bar |

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, flexbox, keyframe animations
- **Vanilla JS** — scroll-triggered sticky header only (~8 lines)
- **Google Fonts** — Cormorant Garamond + Montserrat
- **Unsplash** — free placeholder images via CDN URLs

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
# Just double-click the file, or:
open royal-stranger-clone.html
```

### Option 2 — Serve locally
```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```
Then visit `http://localhost:8000/royal-stranger-clone.html`

---

## 🎨 Design Tokens

All design values are defined as CSS custom properties at the top of the stylesheet:

```css
:root {
  --black:     #0a0a0a;
  --white:     #f9f7f3;
  --cream:     #f2ede5;
  --gold:      #c9a86c;
  --dark-gold: #a8854d;
  --mid:       #6b6560;
  --light:     #e8e2d8;
  --serif:     'Cormorant Garamond', Georgia, serif;
  --sans:      'Montserrat', sans-serif;
}
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Behaviour |
|---|---|
| `> 900px` | Full desktop layout |
| `≤ 900px` | Single-column stacked layout, hidden header actions |

---

## 🖼️ Images

All images are free-to-use placeholder photos sourced from **[Unsplash](https://unsplash.com/)** via their CDN. They are used under the [Unsplash License](https://unsplash.com/license) for demonstration purposes.

To swap in real product images, replace the `src` URLs in the HTML with your own assets.

---

## ⚠️ Disclaimer

This project is a **UI/front-end study clone** created for educational and portfolio purposes only. All branding, copy, and design concepts belong to [Royal Stranger](https://royalstranger.com/). This repository is not affiliated with or endorsed by Royal Stranger.

---

## 📄 License

This clone is released for **personal and educational use only**. Do not use for commercial purposes or redistribute as an original work.
