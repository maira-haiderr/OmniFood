# OmniFood

> A healthy meal delivered to your door, every single day.

OmniFood is a responsive food subscription landing page built with pure HTML, CSS, and JavaScript.

**Live site:** [omnifood-maira.netlify.app](https://omnifood-maira.netlify.app/)

---

## Features

- Responsive layout across desktop, tablet, and mobile
- Smooth scrolling with cross-browser polyfill
- Sticky navigation using the Intersection Observer API
- Mobile hamburger menu
- PWA-ready with `manifest.webmanifest` and multiple favicon sizes
- Runtime Safari flexbox `gap` fix

---

## Project Structure

```
OmniFood/
│
├── index.html                  # Main HTML file
│
├── css/
│   ├── general.css             # Base resets and reusable utility classes
│   ├── style.css               # Component and section styles
│   ├── queries.css             # Media queries for responsiveness
│   └── StylingDecisions.txt    # Design system reference
│
├── js/
│   └── script.js               # Navigation, smooth scroll, sticky header, Safari fix
│
├── img/
│   ├── meals/                  # Meal images
│   ├── gallery/                # Food photo gallery (12 images)
│   ├── customers/              # Customer testimonial photos
│   ├── logos/                  # Press/publication logos
│   └── app/                    # App screen screenshots
│
└── manifest.webmanifest        # Web app manifest for PWA support
```

---

## Tech Stack

| Technology            | Usage                                                    |
| --------------------- | -------------------------------------------------------- |
| HTML5                 | Semantic page structure                                  |
| CSS3                  | Flexbox, Grid, custom properties, media queries          |
| Vanilla JavaScript    | DOM manipulation, Intersection Observer, scroll behavior |
| Google Fonts          | Rubik + Inter typefaces                                  |
| Ionicons 7            | Icon library                                             |
| smoothscroll-polyfill | Cross-browser smooth scrolling                           |

---

## Design System

| Token                   | Value                               |
| ----------------------- | ----------------------------------- |
| Brand color             | `#e67e22`                           |
| Primary tint            | `#fdf2e9`                           |
| Primary shade           | `#cf711f`                           |
| Border radius (default) | `9px`                               |
| Border radius (cards)   | `11px`                              |
| Box shadow              | `0 2.4rem 4.8rem rgba(0,0,0,0.075)` |

**Fonts:** Rubik (headings) · Inter (body)  
**Spacing scale (px):** 2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

---

## Getting Started

No build tools or dependencies needed.

```bash
git clone https://github.com/maira-haiderr/OmniFood.git
cd OmniFood
```

Open `index.html` directly in a browser, or use VS Code's Live Server extension for hot reload.

---

## License

This project is for educational purposes.
