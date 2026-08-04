<div align="center">

<!-- ====== ANIMATED SVG BANNER ====== -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="auto" role="img" aria-label="AURORA SaaS Landing Banner">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#060810"/>
      <stop offset="50%" stop-color="#0c0a1f"/>
      <stop offset="100%" stop-color="#1a0a1e"/>
    </linearGradient>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#8b5cf6"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
    <radialGradient id="orb1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8b5cf6" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#8b5cf6" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#22d3ee" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#22d3ee" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="1200" height="300" fill="url(#bgGrad)"/>
  <circle cx="200" cy="100" r="180" fill="url(#orb1)">
    <animate attributeName="cx" values="200;250;200" dur="10s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1000" cy="220" r="160" fill="url(#orb2)">
    <animate attributeName="cx" values="1000;950;1000" dur="12s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="150" r="120" fill="url(#orb1)" opacity="0.5">
    <animate attributeName="cy" values="150;180;150" dur="8s" repeatCount="indefinite"/>
  </circle>

  <rect x="10" y="10" width="1180" height="280" fill="none" stroke="#8b5cf6" stroke-opacity="0.3" stroke-width="1.5" rx="20"/>
  <rect x="16" y="16" width="1168" height="268" fill="none" stroke="#22d3ee" stroke-opacity="0.12" stroke-width="1" rx="16"/>

  <!-- Logo mark -->
  <text x="110" y="160" text-anchor="middle" font-size="60" fill="url(#grad1)">✦</text>

  <!-- Title -->
  <text x="600" y="115" text-anchor="middle" font-family="Arial, sans-serif" font-size="76" font-weight="bold" fill="url(#grad1)" letter-spacing="6">
    AURORA
  </text>

  <text x="600" y="160" text-anchor="middle" font-family="Arial, sans-serif" font-size="20" letter-spacing="10" fill="#94a3b8">
    SAAS LANDING PAGE
  </text>

  <line x1="380" y1="190" x2="820" y2="190" stroke="url(#grad1)" stroke-opacity="0.6" stroke-width="1.5"/>

  <text x="600" y="228" text-anchor="middle" font-family="Arial, sans-serif" font-size="16" fill="#94a3b8">
    Aurora Gradients · Glassmorphism · Dashboard Mockup · Pricing
  </text>

  <rect x="420" y="250" width="360" height="30" rx="15" fill="#8b5cf6" opacity="0.15"/>
  <text x="600" y="270" text-anchor="middle" font-family="Arial, sans-serif" font-size="13" letter-spacing="3" fill="#c4b5fd">
    PURE HTML/CSS/JS · ZERO DEPENDENCIES
  </text>
</svg>

<!-- ====== BADGES ====== -->
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Glassmorphism-8B5CF6?style=for-the-badge"/>
</p>
<p>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/status-Complete-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/dependencies-ZERO-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/responsive-YES-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/animations-24%2B-orange?style=flat-square"/>
</p>

</div>

---

# ✦ AURORA — SaaS Landing Page

> **A cinematic SaaS landing page** with an animated aurora gradient background, glassmorphism dashboard mockup with live chart bars, 3-tier pricing, and testimonials. **Zero dependencies, zero build step** — open `index.html` and it works.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌈 **Aurora Background** | Three animated gradient orbs drifting in 18s loops |
| 🎛️ **Glassmorphism Mockup** | Browser-frame dashboard with animated chart bars |
| 📈 **Live KPI Cards** | Revenue, users, conversion, retention with deltas |
| 🤖 **AI Insights Feed** | Animated side panel with system events |
| 💎 **Gradient Text** | Animated shifting purple-cyan-pink headlines |
| 💰 **3-Tier Pricing** | Starter / Pro (featured) / Enterprise cards |
| ⭐ **Testimonials** | Client cards with star ratings |
| 📱 **Fully Responsive** | Mobile-first, collapsible nav, fluid grids |

---

## 📂 Project Structure

```
aurora-saas-landing/
├── index.html          ← Complete application (HTML + CSS + JS inline)
└── README.md           ← This file
```

---

## 🎨 Design System

| Element | Value |
|---|---|
| **Fonts** | Outfit (headings + body) — Google Fonts |
| **Primary** | `#8b5cf6` (purple) |
| **Secondary** | `#22d3ee` (cyan) |
| **Tertiary** | `#ec4899` (pink) |
| **Background** | `#060810` (deep space) |
| **Cards** | `rgba(255,255,255,0.04)` glass |
| **Radius** | 16px cards, 100px pills |

---

## 🚀 Quick Start

```bash
# Option 1 — Just open it
open index.html

# Option 2 — Serve locally
python3 -m http.server 8080
# → http://localhost:8080

# Option 3 — Deploy to Vercel / Netlify / GitHub Pages
# Drop the folder in, done — it's static!
```

---

## 📄 Sections Included

1. **Hero** — live pulse badge, gradient headline, dual CTAs
2. **Dashboard Mockup** — browser chrome, animated revenue chart, KPI grid, AI insight feed
3. **Features** — 6 glass cards with gradient hover accents
4. **Pricing** — Starter / Pro (Most Popular) / Enterprise
5. **Testimonials** — 3 client reviews
6. **Final CTA** — gradient banner + primary button
7. **Footer** — brand + legal links

---

## 🧑‍💻 Customization

```css
/* Re-theme in seconds */
:root {
  --purple: #8b5cf6;   /* ← your brand color */
  --cyan: #22d3ee;     /* ← your secondary */
  --pink: #ec4899;     /* ← your accent */
}
```

The dashboard mockup, KPI values, pricing, and testimonials are all plain HTML — edit directly.

---

## 🔖 Tags

`saas` `landing-page` `startup` `glassmorphism` `gradient` `dashboard-mockup` `pricing` `responsive` `template` `html` `css` `javascript` `animation`

---

<div align="center">

**Built with 💀 by [@br-horus](https://github.com/br-horus)** · More projects: [NEXUS](https://github.com/br-horus/nexus-corporate) · [PULSE](https://github.com/br-horus/pulse-admin-dashboard)

⭐ Star this repo if you find it useful!

</div>
