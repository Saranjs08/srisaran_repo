# Srisaran J — Portfolio Website

A modern, responsive, 3D-animated personal portfolio built with pure HTML, CSS, and JavaScript.

## 📁 File Structure

```
portfolio/
├── index.html                    ← Main HTML file (single page)
├── README.md                     ← This file
├── css/
│   └── style.css                 ← All styles, design tokens, animations
├── js/
│   └── main.js                   ← Particle background, typed effect, scroll reveal
├── images/
│   └── (add profile photo here as profile.jpg)
└── certificates/
    ├── aws_cloud_practitioner.jpeg   ← AWS Cloud Practitioner cert image
    └── AWS_CERTIFICATE.pdf           ← AWS Cloud Foundations PDF
```

## ✨ Features

- **Animated particle canvas background** with mouse interaction
- **3D floating card** in hero section with CSS 3D transforms
- **Typed role animation** cycling through skills
- **Scroll reveal** animations on every section
- **Responsive** — works on mobile, tablet, and desktop
- **Active nav highlighting** as you scroll
- **Certificate images** displayed from your uploaded files
- Contact form with success state

## 🎨 Design System

| Token | Value |
|-------|-------|
| `--void` | `#0a0f1e` (deep space background) |
| `--cyan` | `#00d4ff` (primary accent) |
| `--violet` | `#7b2ff7` (secondary accent) |
| Font Display | Space Grotesk |
| Font Body | Inter |
| Font Mono | JetBrains Mono |

## 🚀 How to Use

1. **Open locally:** Double-click `index.html` — works without any server
2. **Add your photo:** Drop a `profile.jpg` in the `images/` folder and update the card avatar in `index.html`
3. **Add resume:** Place your PDF as `Srisaran_Resume.pdf` in the root folder — the Download button is already wired up
4. **Deploy:** Upload the entire `portfolio/` folder to GitHub Pages, Netlify, or Vercel

## 📦 To Deploy on GitHub Pages

```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/Saranjs08/portfolio.git
git push -u origin main
# Enable GitHub Pages in repo Settings → Pages → main branch
```
