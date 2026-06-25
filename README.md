# Purposeful Digital — Lalitha Edupally
## GitHub Pages Portfolio Website

---

## 📁 File Structure

```
purposefuldigital/
├── index.html                        ← Main profile page
├── assets/
│   └── css/
│       └── style.css                 ← All styles
├── casestudies/
│   ├── hllc.html                     ← HLLC case study
│   ├── indus-action.html             ← Indus Action case study
│   ├── techready-women.html          ← TechReady Women Academy
│   ├── intuwellness.html             ← IntuWellness case study
│   └── pilar-indonesia.html          ← Pilar Indonesia case study
└── README.md
```

---

## 🚀 How to Publish on GitHub Pages

1. Go to github.com and create a new repository
2. Name it: `yourusername.github.io`  (replace with your GitHub username)
3. Upload all these files (drag & drop in GitHub UI, or use Git)
4. Go to Settings → Pages → Source: main branch → Save
5. Your site will be live at: `https://yourusername.github.io`

---

## 🖼 Adding Your Photos

Search for these placeholder comments in the HTML files and replace with your actual images:

**index.html (hero photo):**
```html
<!-- Replace the div below with: <img src="assets/images/lalitha-hero.jpg" alt="Lalitha Edupally" /> -->
```

**index.html (about photo):**
```html
<!-- Replace with: <img src="assets/images/lalitha-about.jpg" alt="Lalitha Edupally" /> -->
```

**Case study pages — mockup/project images:**
```html
<!-- <img src="../assets/images/hllc-mockup.jpg" alt="HLLC website mockup" /> -->
```

Create a folder: `assets/images/` and upload your photos there.

**Recommended image sizes:**
- Hero photo: 800×960px (portrait)
- About photo: 700×900px (portrait)
- Case study mockups: 900×600px (landscape)
- Case study thumbnails: 600×400px

---

## 📬 Setting Up the Contact Form (Free)

1. Go to **formspree.io** and create a free account
2. Create a new form → copy your Form ID
3. In `index.html`, find this line:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
4. Replace `YOUR_FORM_ID` with your actual ID
5. Form submissions will go to lalitha.e1505@gmail.com

Formspree free tier: 50 submissions/month (plenty for a portfolio)

---

## ✏️ Customising Content

### Update the tagline
In `index.html`, find:
```html
Digital strategy for organisations that matter
```
Replace with your preferred tagline.

### Update LinkedIn URL
Find: `linkedin.com/in/lalithaedupally`  
Replace with your actual LinkedIn URL.

### Update case study content
Each case study file in `/casestudies/` has clearly marked sections:
- The Challenge
- What I Did  
- The Result
- Quote/testimonial

---

## 🎨 Colour Scheme

The site uses a teal/dark green palette:
- **Primary teal:** `#1B6B5A`
- **Dark teal:** `#144d41`
- **Light teal (backgrounds):** `#e8f3f0`
- **Text dark:** `#1a1a1a`
- **Text mid:** `#444444`

To change colours, edit the `:root` variables at the top of `style.css`.

---

## 📱 Mobile Responsive

The site is fully responsive on all screen sizes. Test it on mobile before publishing.

---

Built with ❤️ for Purposeful Digital
