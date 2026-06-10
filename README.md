# Sameer Pathan — Personal Portfolio Website

> *"I Turn Ideas Into Content, Content Into Attention, And Attention Into Chaos."*

A world-class, Awwwards-level personal portfolio website for **Sameer Pathan** — Digital Creator, Roast Engineer, Comedian, Graphic Designer, and Video Editor.

---

## Live Preview

Deploy this file directly to GitHub Pages and it's live — no build step, no dependencies, no setup.

---

## About This Project

This is a fully self-contained single-file portfolio built to showcase Sameer's creative identity. Every image, font, and animation is either embedded or loaded from a CDN — meaning the file works offline once loaded and deploys to GitHub Pages in one upload.

The design language is **Ultra-Dark Cyberpunk Luxury** — think Apple meets Tesla meets the Creator Economy, with neon blue and purple as the core palette.

---

## Features

### Visual Design
- Ultra-dark black background with neon blue (`#00f0ff`) and purple (`#7b2fff`) accents
- Glassmorphism cards and panels throughout
- Glitch text effect on the hero name
- Film grain noise overlay and scanline texture for cyberpunk feel
- Three animated breathing orbs in the background

### Animations & Interactions
- **Three.js 3D background** — rotating torus rings, wireframe icosahedrons, star field, and floating neon particles all reacting to mouse movement
- **Aurora wave canvas** — four layered sine waves in neon colors flowing continuously behind the content
- **Custom cursor** — glowing dot with a lagging ring trail
- **GSAP-powered entrance** — hero section animates in with staggered reveals on load
- **Scroll-triggered animations** — every section fades and slides in as you scroll
- **3D tilt on hero photo** — perspective rotation follows mouse position
- **Floating photos** — three photos fixed on screen that parallax with mouse movement
- **Typing effect** — cycles through 10 creative titles in the hero section
- **Animated quote carousel** — rotates through 6 quotes with dot navigation
- **Counter animation** — stats count up from zero when scrolled into view
- **Skill card tilt** — 3D perspective tilt on hover for each skill card

### Sections
| Section | Description |
|---|---|
| Hero | Full-screen cinematic entrance with name, typing text, tagline, and photo frame |
| About | Bio with 4-photo grid and personality tags |
| Skills | 10 animated floating skill cards |
| Stats | Animated counters — roasts, designs, videos, laughs |
| Portfolio | 6 project cards with category filters |
| Gallery | Masonry photo wall with all uploaded photos |
| Quotes | Auto-rotating quote carousel |
| Timeline | Career origin story with glowing vertical line |
| Contact | Contact form + social media links |

### Social Links
- **Instagram** — [@mister_sam_0786](https://www.instagram.com/mister_sam_0786)
- YouTube, LinkedIn, Email, X (Twitter) — update links in the contact section

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 | Animations, glassmorphism, responsive layout |
| JavaScript (Vanilla) | All interactivity and logic |
| [Three.js r128](https://threejs.org/) | 3D background — particles, rings, geometry |
| [GSAP 3.12](https://greensock.com/gsap/) | Scroll animations, entrance transitions, quote fade |
| Google Fonts | Space Grotesk + Bebas Neue |

---

## Deployment — GitHub Pages

### Step 1 — Create Repository
```
Go to github.com → New repository
Name it: sameer-pathan-portfolio (or any name)
Set to Public
Do NOT initialise with README
```

### Step 2 — Upload File
```
Click "uploading an existing file"
Drag and drop index.html
Commit changes
```

### Step 3 — Enable GitHub Pages
```
Repository → Settings → Pages
Source: Deploy from a branch
Branch: main → / (root)
Save
```

### Step 4 — Your site is live at
```
https://yourusername.github.io/sameer-pathan-portfolio
```

> Takes 1–2 minutes to go live after enabling Pages.

---

## Customisation Guide

### Update Social Links
Find the `socials` section near the bottom of `index.html`:

```html
<a class="soc" href="https://www.instagram.com/mister_sam_0786" ...>
<a class="soc" href="YOUR_YOUTUBE_LINK" ...>
<a class="soc" href="YOUR_LINKEDIN_LINK" ...>
<a class="soc" href="mailto:YOUR_EMAIL" ...>
```

### Update Contact Email
```html
<a class="soc" href="mailto:your@email.com" title="Email">
```

### Change Typing Words
Find `var WORDS = [...]` in the script section and edit the array.

### Add New Portfolio Projects
Duplicate any `.pf-card` block inside `#portfolio` and update the image, category, title, and description.

### Swap Photos
The 5 photos are embedded as base64 strings. To replace a photo, convert your new image to base64 and replace the `data:image/png;base64,...` string for that image.

---

## Project Structure

```
index.html          ← Entire website (single file, ~4MB with embedded photos)
README.md           ← This file
```

---

## Credits

**Design & Development** — Built for Sameer Pathan  
**Photos** — Sameer Pathan  
**Fonts** — Google Fonts (Space Grotesk, Bebas Neue)  
**3D Engine** — Three.js  
**Animation** — GSAP by GreenSock  

---

## License

This project is personal and built exclusively for Sameer Pathan. All photos and personal branding belong to the subject. The code structure is free to reference for learning purposes.

---

<div align="center">

**Made with chaos, creativity, and zero sleep.**

[![Instagram](https://img.shields.io/badge/Instagram-@mister__sam__0786-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/mister_sam_0786)

</div>
