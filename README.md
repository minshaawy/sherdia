# Dr. Abdullah Sherdia — Dental Clinic Website

موقع رسمي لعيادة د. عبدالله محمد شردية لطب وتجميل وزراعة الأسنان.

Single-page bilingual (Arabic/English) website for Dr. Abdullah Sherdia's dental clinic, with two branches and direct WhatsApp booking integration.

---

## ✨ Features

- 🌍 **Arabic-first RTL layout** with bilingual support
- 📱 **Fully responsive** — mobile-first design with breakpoints for tablet & desktop
- 💬 **WhatsApp integration** — every CTA opens a pre-filled chat with the clinic
- 🗺️ **Google Maps integration** — direct location links for each branch
- 🖼️ **Cases gallery with lightbox** — click to enlarge, swipe & keyboard navigation
- 🔍 **SEO optimized** — meta tags, Open Graph, structured data (Schema.org)
- ⚡ **Single HTML file** — no build process, no dependencies, instant load
- 🎨 **Editorial medical aesthetic** — IBM Plex Sans Arabic + Inter typography

---

## 📁 Files

```
.
├── index.html          # Main website (single file, all CSS + JS inline)
├── doctor.jpg          # Doctor's portrait (used in Hero & About sections)
├── cases/              # Folder for case photos
│   └── README.txt      # Instructions for adding case images
├── README.md           # This file
├── robots.txt          # Search engine instructions
├── .gitignore          # Git ignore rules
└── .nojekyll           # Disables Jekyll on GitHub Pages
```

---

## 🚀 Deploy on GitHub Pages

1. **Create a new repository** on GitHub (e.g., `sherdia-clinic`)
2. **Upload these files** to the root of the repo:
   - `index.html`
   - `doctor.jpg`
3. Go to **Settings → Pages**
4. Under **Source**, select branch `main` and folder `/ (root)`
5. Click **Save**
6. Your site will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 🛠️ Customization

### Update branch addresses

Open `index.html` and search for `[العنوان التفصيلي للفرع`. Replace the placeholder text with the real addresses for both branches.

### Update WhatsApp number

The phone number `+201023282361` appears in multiple places. Use Find & Replace in your editor to change it everywhere at once if needed.

### Update doctor photo

Replace `doctor.jpg` with your own image. For best results:
- Aspect ratio: **9:16** (portrait)
- Resolution: at least **1200×2133px**
- Format: JPG or WebP

If your image has a different aspect ratio, edit `index.html` and search for `aspect-ratio: 9/16` — change it to match your image (e.g., `4/5` or `3/4`).

### Add case photos to gallery

1. Place images in the `cases/` folder, named `case-1.jpg`, `case-2.jpg`, etc.
2. Open `index.html` and find each `<!-- <img src="cases/case-N.jpg" -->` line
3. Remove the `<!--` and `-->` around the `<img>` tag
4. Delete the `<div class="placeholder">...</div>` block right below it
5. Update the `data-caption` and `<div class="label">` text for each case

Recommended: square images (1:1 ratio), ~1000×1000px, JPG/WebP, under 500KB each.

### Update second branch map link

Search for `<a href="#" class="branch-btn map">` (the second occurrence) and replace `#` with the Google Maps link for the second branch.

---

## 📝 Tech Stack

- Vanilla HTML + CSS (no framework)
- Google Fonts: IBM Plex Sans Arabic, Inter
- No JavaScript dependencies
- No build step required

---

## 📞 Contact

- **Phone / WhatsApp:** +20 102 328 2361
- **Branch 1 (City Dental Clinic):** [Google Maps](https://maps.app.goo.gl/JNqTKjRrJGR4BKUB6)

---

© 2026 — Dr. Abdullah Sherdia Dental Clinic
