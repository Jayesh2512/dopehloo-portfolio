# 🎬 DO PEHLOO — Independent Film Production House

> *"Two sides to every frame. Zero compromise on story."*

Official portfolio website for **Do Pehloo**, an independent Delhi-based film production collective crafting narrative short films, music videos, and commercial visuals.

🔗 **Repository:** [github.com/Jayesh2512/dopehloo-portfolio](https://github.com/Jayesh2512/dopehloo-portfolio)  
📺 **YouTube:** [@DoPehloo](https://www.youtube.com/@DoPehloo)  
📸 **Instagram:** [@dopehloo](https://www.instagram.com/dopehloo/)  
✉️ **Email:** `dopehloo@gmail.com`

---

## ✨ Design & Features

- **Strict Black & White Monochrome:** High-contrast 35mm B&W film aesthetic with subtle scanlines, sprocket dividers, and monochrome media filtering.
- **Minecraft-Style Pixel Typography:** Powered by *Silkscreen*, *Pixelify Sans*, and *VT323*.
- **No Navigation Bar (Mobile Responsive):** All four page switches (`[ HOME ]`, `[ WORK ]`, `[ ABOUT US ]`, `[ CONTACT US ]`) sit directly at the top and adapt cleanly to mobile screens.
- **Old Cinema Theatre Home Screen:** Features theatre curtains, a glowing cinema projection screen, and silhouette seating.
- **Screening Room Lightbox:** Interactive video modal with category filtering (*Short Films*, *Music Videos*, *Commercials*) and `strict-origin-when-cross-origin` referrer headers configured via `vercel.json` for reliable YouTube embeds.
- **Official Government-Style Contact Form:** Styled as *Directorate of Visual Storytelling (Form DP-2026)* with direct email dispatch to `dopehloo@gmail.com` via FormSubmit and a built-in `mailto:` fallback.

---

## 🏆 Achievements & Collaborations

### Festival Honors
- **Vespera — GGSIPU Delhi:** 1st Place for Short Film Making

### Brand & Client Collaborations
- **Kroslo** — Visual storytelling & brand video production
- **Myntra** — Fashion & lifestyle visual campaign work
- **Find My Kids** — Digital ad & narrative commercial production
- **Sparx** — Commercial test shoot

---

## 🎞️ Selected Filmography

| Reel | Title | Category | Duration |
| :--- | :--- | :--- | :--- |
| `REEL 01` | **Gemini \| A Short Film** | Short Film | `05:35` |
| `REEL 02` | **Sparx AD \| Test Shoot** | Commercial | `01:29` |
| `REEL 03` | **Akatsuki \| Seedhe Maut ft. Raga (Unofficial MV)** | Music Video | `02:38` |
| `REEL 04` | **Sutta \| Short Film \| Do Pehloo** | Short Film | `03:16` |

---

## 👥 The Crew

| Name | Role | Instagram |
| :--- | :--- | :--- |
| **Surya** | Director, Editor | [@sun_that_never_shades](https://www.instagram.com/sun_that_never_shades/) |
| **Dhruv** | Cinematographer | [@notdhruv.exe](https://www.instagram.com/notdhruv.exe/) |
| **Jayesh** | Writer | [@jae.hashhh](https://www.instagram.com/jae.hashhh/) |
| **Souhard** | Writer | [@sohardnahisouhard](https://www.instagram.com/sohardnahisouhard/) |

---

## 📁 Project Structure

```text
dopehloo-portfolio/
├── index.html          # Complete single-file portfolio (HTML, CSS, JS)
├── vercel.json         # HTTP headers config (Referrer-Policy for YouTube embeds)
├── README.md           # Project documentation
└── assets/
    ├── surya.jpg       # Crew portrait (Surya)
    ├── dhruv.jpg       # Crew portrait (Dhruv)
    ├── jayesh.jpg      # Crew portrait (Jayesh)
    ├── souhard.jpg     # Crew portrait (Souhard)
    └── sutta.jpg       # Short film thumbnail (Sutta)
```

---

## 🚀 Deployment (Vercel)

This is a zero-build static site—no Node.js, npm, or bundler required.

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
2. Click **Add New → Project** and import `Jayesh2512/dopehloo-portfolio`.
3. Keep all framework/build settings as default and click **Deploy**.
4. **Activate Contact Form:** Submit one test inquiry on your live Vercel URL, then open `dopehloo@gmail.com` and click the one-time **Activate** link from FormSubmit.

### Optional: Updating Content
- **Add inline playback for *Sutta*:** Open `index.html`, search for `id: 'sutta'`, and paste the 11-character YouTube video ID into `videoId: ''`.
- **Add new films:** Append a new object to the `PROJECTS` array inside `index.html`.

---

*Built for **Do Pehloo** — Delhi, India.*
