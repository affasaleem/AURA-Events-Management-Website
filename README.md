


## 📂 Project Structure

```text
event-management-website/
│
├── index.html          # Main entry page (Semantic structure & JS controllers)
├── style.css           # Core styling, variables, keyframes, glassmorphism tokens
├── responsive.css      # Breakpoints adjustments from 1400px down to 320px
│
├── assets/
│   ├── images/         # Real high-resolution stock event photos
│   │   ├── hero-event.jpg
│   │   ├── about-event.jpg
│   │   ├── corporate-event.jpg
│   │   ├── wedding-event.jpg
│   │   ├── concert-event.jpg
│   │   ├── speaker-1.jpg
│   │   ├── speaker-2.jpg
│   │   ├── speaker-3.jpg
│   │   ├── gallery-1.jpg
│   │   ├── gallery-2.jpg
│   │   ├── gallery-3.jpg
│   │   └── testimonial-avatar.jpg
│   │
│   └── icons/          # Reserved for custom SVGs/assets
│
└── README.md           # Project documentation and guide
```

---

## 🛠️ Technology Stack

1. **HTML5**: Semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`) ensuring accessibility and neat SEO architecture.
2. **CSS3**: Custom property variables, Grid templates, Flex flows, backdrop filter styling, and keyframe animations.
3. **Vanilla JS**: Lightweight controllers for responsive interactive elements (zero third-party JS dependencies for layout).
4. **Google Fonts**: Importing `Space Grotesk` (headings) and `Plus Jakarta Sans` (body).
5. **FontAwesome v6**: Crisp vectors for services, benefits, contact icons, and rating indicators loaded via CDN.

---

## 🚀 How to Run Locally

1. Open the project folder on your system.
2. Double-click `index.html` to open it in any modern browser (Chrome, Safari, Edge, Firefox).
3. Alternatively, run a local development server (e.g., Live Server extension in VS Code, or python server):
   ```bash
   # Python 3
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.
