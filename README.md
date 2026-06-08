# nukkad 🏪

> Digital presence for a beloved neighbourhood stationery & document shop in Baghpat, U.P.

<br/>

![Made with HTML CSS JS](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-E8640A?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-2D7A4F?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-D4A24C?style=flat-square)
![No Build Step](https://img.shields.io/badge/Build%20Step-None-555?style=flat-square)

<br/>

## 🏠 About

**D.K. Photo Stat & Book Depot** is a trusted local institution in Bara Bazar, Baghpat, Uttar Pradesh — two shops running side by side, owned and operated by brothers **Neeraj Kumar Jain** (elder) and **Dheeraj Kumar Jain**.

This project is a single-file, fully responsive website built to give the shop a professional online presence — helping students, job seekers, and local residents discover their services and get in touch easily.

<br/>

## 🖼️ Preview

| Desktop                                    | Mobile                         |
| ------------------------------------------ | ------------------------------ |
| Sidebar navigation, full-viewport sections | Bottom tab bar, stacked layout |

> Dark editorial aesthetic — warm saffron + antique gold + forest green on near-black background.

<br/>

## 🛍️ The Businesses

### 📚 D.K. Book Depot

**Owner:** Neeraj Kumar Jain (Elder Brother)
**Contact:** [8279660273](tel:+918279660273) · [WhatsApp](https://wa.me/918279660273)

| Service                   | Details                                                           |
| ------------------------- | ----------------------------------------------------------------- |
| Stationery                | All types and all brands                                          |
| Spiral Binding            | A4 and FS size                                                    |
| Form Filling              | Government jobs, private jobs, competitive exams, admission forms |
| Cloud & WhatsApp Printing | Send files on WhatsApp or from Google Drive                       |

---

### 📠 D.K. Photo Stat

**Owner:** Dheeraj Kumar Jain
**Contact:** [9997190959](tel:+919997190959) · [WhatsApp](https://wa.me/919997190959)

| Service                   | Details                                     |
| ------------------------- | ------------------------------------------- |
| Xerox / Photocopying      | Black & White and Colour                    |
| Paper Sizes               | Aadhaar card size all the way to A1 poster  |
| Lamination                | Soft and Hard both available                |
| Cloud & WhatsApp Printing | Send files on WhatsApp or from Google Drive |

---

### 🎉 Seasonal & Special

- 🇮🇳 **Republic Day (26th Jan)** — Patriotic items, flags, tricolour accessories
- 🏳️ **Independence Day (15th Aug)** — Kites, flags, festive supplies
- 🪔 **Diwali** — Home decoration items and festive accessories
- 📅 **Open 365 days a year** — No exceptions

<br/>

## 📍 Location

**Bara Bazar, Baghpat, Uttar Pradesh — 250609**

[View on Google Maps →](https://maps.app.goo.gl/gZtV4xNpHsNMLZet5)

<br/>

## ✨ Features

- **Fixed sidebar navigation** — collapses to 64px, expands to 230px on hover (inspired by [uditjain100.github.io](https://uditjain100.github.io))
- **Mobile bottom tab bar** — sidebar becomes a sticky bottom nav on screens under 900px
- **Hero text animation** — staggered word-by-word entrance on page load
- **Scroll reveal** — every section fades in + slides up via IntersectionObserver
- **Active section tracking** — sidebar highlights the current section as you scroll
- **Hover micro-interactions** — cards lift, stats slide, service cards glow
- **Floating WhatsApp buttons** — pulsing ring animation, one per shop
- **Grain texture overlay** — subtle paper-like noise across the entire page
- **Google Maps embed** — iframe pointing to the exact shop location
- **Click-to-call links** — all phone numbers are tappable on mobile
- **wa.me WhatsApp links** — deep links open WhatsApp directly
- **Base64 embedded photo** — brothers' photo baked into the HTML, no external file needed
- **Fully self-contained** — one `.html` file, zero dependencies, zero build step

<br/>

## 🎨 Design System

### Color Palette

| Token      | Hex       | Usage                             |
| ---------- | --------- | --------------------------------- |
| Background | `#0F0B07` | Page base                         |
| Surface    | `#1A1410` | Cards, sidebar                    |
| Saffron    | `#E8640A` | D.K. Photo Stat accent, CTAs      |
| Gold       | `#D4A24C` | Decorative accents, active states |
| Green      | `#2D7A4F` | D.K. Book Depot accent            |
| Cream      | `#F5EDD8` | Primary text                      |
| Muted      | `#8A7A65` | Secondary text                    |

### Typography

| Role               | Font               | Weight                   |
| ------------------ | ------------------ | ------------------------ |
| Display / Headings | Cormorant Garamond | 700 (italic for accents) |
| Body / UI          | DM Sans            | 300, 400, 500, 600       |

Both loaded via Google Fonts CDN.

### Layout

- Fixed 64px sidebar → expands to 230px on hover
- Full-viewport sections (`min-height: 100vh`)
- CSS Grid for service cards, about section, contact grid
- `auto-fit minmax()` for responsive why-us and seasonal grids

<br/>

## 🗂️ Sections

| #   | Section      | Description                                                       |
| --- | ------------ | ----------------------------------------------------------------- |
| 1   | **Hero**     | Shop name, Hindi tagline, dual WhatsApp CTAs, open-365-days badge |
| 2   | **About**    | Brothers' story, photo, key stats                                 |
| 3   | **Services** | Two shop cards — Book Depot (green) and Photo Stat (saffron)      |
| 4   | **Why Us**   | 6 trust-building points with numbered cards                       |
| 5   | **Seasonal** | Republic Day, Independence Day, Diwali, always-open callout       |
| 6   | **Contact**  | Click-to-call, WhatsApp links, address, Google Maps iframe        |
| 7   | **Footer**   | Shop name, tagline, quick links, both numbers                     |

<br/>

## 🚀 Deployment

This is a **zero-dependency, single HTML file**. No npm, no build step, no framework.

### Option 1 — Netlify Drop (Recommended, Free)

1. Download `dk_photostat_v2.html`
2. Go to [netlify.com/drop](https://netlify.com/drop)
3. Drag and drop the file
4. Live in 30 seconds ✅

### Option 2 — GitHub Pages

1. Push `dk_photostat_v2.html` to this repo
2. Rename it to `index.html`
3. Go to **Settings → Pages → Source → main branch**
4. Your site will be live at `https://<username>.github.io/nukkad`

### Option 3 — Any Static Host

Upload `index.html` to any web host that serves static files (Vercel, Render, shared hosting, etc.)

<br/>

## 🗺️ Project Structure

```
nukkad/
│
├── index.html          # The entire website (HTML + CSS + JS + base64 image)
└── README.md           # This file
```

Everything lives in one file by design — easy to share, deploy, and maintain without any tooling.

<br/>

## 🛠️ Tech Stack

| Layer     | Choice                             | Reason                                       |
| --------- | ---------------------------------- | -------------------------------------------- |
| Markup    | HTML5 (semantic)                   | Accessibility, SEO-friendly structure        |
| Styling   | Vanilla CSS with custom properties | Zero runtime overhead                        |
| Scripting | Vanilla JS                         | IntersectionObserver for scroll & active nav |
| Fonts     | Google Fonts CDN                   | Cormorant Garamond + DM Sans                 |
| Images    | Base64 embedded                    | Self-contained, no broken image links        |
| Maps      | Google Maps iframe                 | Direct embed, no API key needed              |

<br/>

## 📱 Responsive Breakpoints

| Breakpoint | Layout                                  |
| ---------- | --------------------------------------- |
| `> 900px`  | Fixed sidebar + scrollable main content |
| `≤ 900px`  | No sidebar; bottom tab bar appears      |
| `≤ 600px`  | Single-column grids, stacked CTAs       |
| `≤ 400px`  | Fully single-column                     |

<br/>

## ✅ Checklist

- [x] Both shop service cards clearly separated
- [x] Book Depot (Neeraj, elder brother) listed first everywhere
- [x] Both WhatsApp numbers correct and use `wa.me` format
- [x] Phone numbers are click-to-call `<a href="tel:...">` links
- [x] Google Maps iframe embedded
- [x] Fully responsive at 375px, 768px, and 1280px
- [x] No horizontal scroll on any viewport
- [x] Grain texture visible but subtle
- [x] Hero text animates on load
- [x] Sections animate on scroll
- [x] Active section highlighted in sidebar as user scrolls
- [x] Brothers' photo shows heads (object-position: top)
- [x] Open 365 days badge with live pulse indicator

<br/>

## 📞 Contact

| Shop            | Owner              | Phone                           | WhatsApp                           |
| --------------- | ------------------ | ------------------------------- | ---------------------------------- |
| D.K. Book Depot | Neeraj Kumar Jain  | [8279660273](tel:+918279660273) | [Chat](https://wa.me/918279660273) |
| D.K. Photo Stat | Dheeraj Kumar Jain | [9997190959](tel:+919997190959) | [Chat](https://wa.me/919997190959) |

**Address:** Bara Bazar, Baghpat, Uttar Pradesh — 250609

<br/>

## 📄 License

MIT — free to use, modify, and deploy.

---

<p align="center">Built with ❤️ for the Jain brothers of Bara Bazar, Baghpat</p>
