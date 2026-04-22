# Cosmicol Limited — Website

Professional 4-page website for **Cosmicol Limited**, Ndola, Zambia.

## 📁 Project Structure

```
cosmicol/
├── index.html          ← Home page
├── about.html          ← About Us
├── gallery.html        ← Portfolio Gallery
├── contact.html        ← Contact page
├── assets/
│   ├── css/
│   │   └── style.css   ← All shared styles
│   ├── js/
│   │   ├── main.js     ← Navbar, hamburger menu
│   │   └── gallery.js  ← Gallery data & logic ← EDIT THIS TO ADD IMAGES
│   └── images/
│       └── img-01.jpg ... img-20.jpg
└── README.md
```

---

## 🖼️ How to Add New Gallery Images

1. Copy the new image file into `assets/images/`
2. Open `assets/js/gallery.js`
3. Add a new entry to the `GALLERY_IMAGES` array at the top:

```js
{ src: "assets/images/your-new-image.jpg", category: "Billboard", caption: "Your Caption Here" },
```

Available categories: `Billboard`, `Vehicle Branding`, `Corporate Gifts`, `Signage`, `Print`

---

## 🚀 Deploy to Netlify via GitHub

### First-time setup:
```bash
# 1. Create a new GitHub repo (e.g. "cosmicol-website")
# 2. Run these commands in the cosmicol folder:

git init
git add .
git commit -m "Initial commit — Cosmicol website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/cosmicol-website.git
git push -u origin main
```

### Connect to Netlify:
1. Go to [netlify.com](https://netlify.com) → **Add new site** → **Import from Git**
2. Choose your GitHub repo
3. Build settings: leave blank (static HTML site)
4. Click **Deploy Site** — done! 🎉

### Update the site later:
```bash
git add .
git commit -m "Update gallery images"
git push
```
Netlify auto-deploys on every push.

---

## 📞 Contact Info on the Site
- Phone: 0974 975 099 / 0960 166 465
- Email: info@cosmicoldigital.com
- WhatsApp: wa.me/260974975099
- Location: Ndola, Zambia
