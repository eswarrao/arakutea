# ARAKU TEA — Luxury Scroll-Driven Website

A premium single-page website for **Araku Tea**, featuring a scroll-driven video hero, GSAP animations, and a fully inline HTML/CSS/JS build served by Express.

---

## Prerequisites

Make sure you have the following installed before running:

| Tool | Minimum Version | Download |
|------|----------------|----------|
| Node.js | v16 or higher | https://nodejs.org |
| npm | v7 or higher | Included with Node.js |
| Git | Any | https://git-scm.com |

---

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/eswarrao/arakutea.git
cd arakutea
```

### 2. Install dependencies

```bash
npm install
```

> This only installs **Express** — there are no other dependencies.

### 3. Start the server

```bash
node server.js
```

You should see:

```
ARAKU TEA running at http://localhost:3000
```

### 4. Open in browser

```
http://localhost:3000
```

---

## Project Structure

```
arakutea/
├── server.js              ← Express static server (port 3000)
├── package.json
├── .gitignore
└── public/
    ├── index.html         ← Entire website (HTML + CSS + JS inline)
    ├── tea-story-final.mp4← Scroll-driven hero video
    ├── dawn-product.jpg   ← DAWN card product image
    ├── dusk-product.jpg   ← NOON card product image
    └── night-product.jpg  ← NIGHT card product image
```

---

## Features

- **Scroll-driven video** — hero video plays automatically via auto-scroll; frames extracted using `requestVideoFrameCallback` for smooth, lag-free playback
- **Auto-scroll** — video plays on its own at load; user can interrupt with mouse wheel or touch
- **GSAP + ScrollTrigger** — all sections animate in on scroll
- **Product cards** — DAWN · NOON · NIGHT with hover effects
- **Contact modal** — phone, email, and location popup
- **Scroll-to-top button** — restarts the video from the beginning
- **Fully inline** — no build step, no bundler, no framework

---

## Stopping the Server

Press `Ctrl + C` in the terminal.

---

## Running on a Different Port

Edit `server.js` and change the port number:

```js
app.listen(4000, () => console.log('ARAKU TEA running at http://localhost:4000'));
```

---

## Contact

**Eswara Bailapudi**  
📧 eswar.bailapudi@gmail.com  
📞 +91 95915 69413  
📍 Visakhapatnam, Andhra Pradesh

---

*© 2026 Araku Tea. All rights reserved.*
