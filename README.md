# Syed Navan Nahiyan — Personal Portfolio

[![Live Site](https://img.shields.io/badge/Live_Portfolio-n4van.github.io-E04E35?style=flat&logo=github)](https://n4van.github.io/navan.github.io/)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-24292e?style=flat&logo=github-pages)](https://n4van.github.io/navan.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Personal portfolio website for **Syed Navan Nahiyan** — Business Administration student at Primeasia University and Operations Lead with 5+ years of experience in event management, project execution, and organizational leadership.

---

## 🌟 Features

- **⚡ Fast & Lightweight:** 100% vanilla HTML5, CSS3, and JavaScript — zero external framework dependencies, instant load times, and perfect Lighthouse performance.
- **🌓 Dark & Light Mode:** Seamless theme switching with OS preference detection, manual toggle switch, and `localStorage` persistence.
- **📱 Fully Responsive:** Clean layout designed for every screen size from mobile smartphones (320px) to ultra-wide displays (4K).
- **🔍 Filterable Initiatives Showcase:** Interactive project filtering tabs (*All*, *Operations & Logistics*, *Event Leadership*, *Competitions & Strategy*).
- **🖼️ Interactive Photo Lightbox:** Fullscreen modal with smooth transitions and keyboard accessibility (ESC key to dismiss) to showcase campus events, competitions, and trips.
- **📋 One-Click Copy & Toast Alerts:** Instant clipboard copy for email and phone numbers with animated confirmation toasts.
- **💬 Direct WhatsApp Chat Integration:** One-click direct messaging link for instant business communication.
- **🌐 SEO & Social Sharing:** Preconfigured Open Graph (`og:*`) tags and Twitter cards for rich previews when shared on LinkedIn, WhatsApp, or Twitter.

---

## 📂 Project Structure

```
navan.github.io/
├── index.html        # Main semantic HTML5 document
├── styles.css        # Design system, CSS variables, dark/light themes, animations
├── script.js         # Theme toggle, lightbox modal, project filtering, toast notifications
├── README.md         # Repository documentation
└── assets/
    └── images/       # High-resolution photographic assets
        ├── canon-shot.jpg           # Hero camera portrait
        ├── hero-suit.jpg            # Formal portrait alternative
        ├── headshot.jpg             # Studio headshot
        ├── portrait-street.jpg      # Contact section outdoor portrait
        ├── freshers-fiesta-1.jpg    # PAUBC event photo
        ├── freshers-fiesta-2.jpg    # PAUBC event photo
        ├── iftar-mahfil.jpg         # Central Iftar Mahfil event
        ├── football-tournament.jpg  # Intra Football Tournament
        ├── business-genius-10.jpg   # National Business Genius competition
        └── coxs-bazar.jpg           # Annual trip photo
```

---

## 🚀 How to Deploy to GitHub Pages

1. **Commit & Push Changes:**
   ```bash
   git add .
   git commit -m "Modernize portfolio: add dark mode, lightbox, project filters, and clean styling"
   git push origin main
   ```

2. **Verify GitHub Pages Settings:**
   - Go to your repository on GitHub: `https://github.com/n4van/navan.github.io`
   - Navigate to **Settings** > **Pages** (in the left sidebar).
   - Under **Build and deployment**:
     - **Source**: `Deploy from a branch`
     - **Branch**: `main` / `root`
   - Click **Save**.
   - Your site will be published at: **`https://n4van.github.io/navan.github.io/`** (or `https://n4van.github.io/` if configured as the user root site).

---

## 🛠️ Customization Guide

### 1. Changing the Hero Photo
To switch from `canon-shot.jpg` to the formal suit photo `hero-suit.jpg`, simply edit line 105 in `index.html`:
```html
<img src="assets/images/hero-suit.jpg" alt="Syed Navan Nahiyan, portrait" loading="eager">
```

### 2. Adding a PDF Resume / CV
Place your resume PDF in `assets/resume.pdf` and add the download button in `index.html` under `.hero-actions`:
```html
<a href="assets/resume.pdf" target="_blank" download class="btn-accent">
  Download CV &darr;
</a>
```

### 3. Adding New Projects
Copy any `.project-card` block inside the `<div class="projects-grid">` section in `index.html`, and set the `data-category` attribute to match the relevant filter tabs:
```html
<div class="project-card" data-category="operations">
  ...
</div>
```

---

## 📄 License
Released under the [MIT License](LICENSE).
