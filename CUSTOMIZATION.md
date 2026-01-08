# Portfolio Customization Quick Reference

## 🎯 Key Things to Customize

### 1. YOUR NAME/BRAND
**File:** index.html | **Location:** Header section
```html
<div class="logo">🐉 YOUR NAME HERE</div>
```

### 2. HERO HEADING & SUBTITLE
**File:** index.html | **Location:** Hero section
```html
<h1>Your Professional Title</h1>
<p>Your tagline or professional summary</p>
```

### 3. ABOUT ME SECTION
**File:** index.html | **Location:** About section
Replace the paragraphs with your background, experience, and goals.

### 4. SKILLS
**File:** index.html | **Location:** Skills section
Update the skill categories and items to match your expertise.

### 5. PROJECTS
**File:** index.html | **Location:** Projects section
Replace sample projects with your actual work. Each project card includes:
- Title
- Description
- Technology tags
- Link to project

### 6. SOCIAL LINKS & CONTACT
**File:** index.html | **Location:** Contact section

Update these URLs:
```html
<a href="https://github.com/YOUR_USERNAME" ...>
<a href="https://linkedin.com/in/YOUR_PROFILE" ...>
<a href="mailto:your-email@gmail.com" ...>
```

### 7. CONTACT FORM
**File:** index.html | **Location:** Contact form

Currently the form action is a placeholder. To make it work:

**Option A: Use Formspree (Recommended)**
1. Visit https://formspree.io
2. Create account and setup form
3. Replace the action URL:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option B: Use Email Link**
```html
<form class="contact-form" action="mailto:your-email@gmail.com" method="POST" enctype="text/plain">
```

---

## 🎨 CHANGE COLORS

Find these color codes in the CSS section and replace:

**Primary Color (Blue-Purple):**
- Replace `#667eea` with your color code

**Secondary Color (Dark Purple):**
- Replace `#764ba2` with your color code

**Text Color (Dark Gray):**
- Replace `#333` with your color code

**Background Color (Light Gray):**
- Replace `#f4f4f4` with your color code

---

## 📱 RESPONSIVE DESIGN

The portfolio automatically adapts to all screen sizes:
- ✅ Desktop (1200px and above)
- ✅ Tablets (768px - 1199px)
- ✅ Mobile (below 768px)

No changes needed - it's already built in!

---

## 🔗 NAVIGATION ANCHORS

Make sure your links match the section IDs:

```html
<!-- Navigation Link -->
<a href="#projects">Projects</a>

<!-- Section it links to -->
<section id="projects">
```

Current sections:
- `#home` - Hero section
- `#about` - About me
- `#projects` - Featured projects
- `#skills` - Skills
- `#contact` - Contact form

---

## 📸 ADDING IMAGES

To add images, use this code:
```html
<img src="path-to-image.jpg" alt="Description of image">
```

Example - Add profile photo in About section:
```html
<img src="images/profile.jpg" alt="My professional photo" 
     style="width: 200px; height: 200px; border-radius: 50%;">
```

---

## 🔍 FILE STRUCTURE

```
addictiondragon.github.io/
├── index.html          (Your main webpage)
├── README.md           (Documentation)
├── CUSTOMIZATION.md    (This file)
└── images/             (Create this folder for your photos)
    ├── profile.jpg
    └── project1.jpg
```

---

## ✅ BEFORE YOU DEPLOY

- [ ] Updated your name and logo
- [ ] Added your bio in About section
- [ ] Listed your actual skills
- [ ] Added your real projects
- [ ] Updated social media links
- [ ] Set up contact form
- [ ] Tested on mobile device
- [ ] Checked all links work
- [ ] Added a profile photo

---

## 🚀 DEPLOYMENT CHECKLIST

### If using GitHub Pages:
1. Create repo named `username.github.io`
2. Upload `index.html` and `images/` folder
3. Your site goes live at `https://username.github.io`

### If using Netlify or Vercel:
1. Connect your GitHub account
2. Import the repository
3. Deploy with one click

---

## 💬 COMMON QUESTIONS

**Q: How do I add more projects?**
A: Copy an entire `<div class="project-card">` block and paste it. Update the content.

**Q: Can I change the font?**
A: Yes! Find `font-family: 'Segoe UI'...` in CSS and replace with your font choice.

**Q: How do I make the form actually send emails?**
A: Use Formspree.io (free) - see Contact Form section above.

**Q: The page looks broken on my phone?**
A: That shouldn't happen - it's responsive. Try clearing cache (Ctrl+Shift+Delete).

**Q: Can I use this for multiple portfolios?**
A: Yes! Just save as different files like `portfolio.html` or `resume.html`.

---

## 📖 HELPFUL RESOURCES

- **HTML Reference:** https://www.w3schools.com/html/
- **CSS Reference:** https://www.w3schools.com/css/
- **Color Picker:** https://htmlcolorcodes.com/
- **Font Awesome Icons:** https://fontawesome.com/
- **Free Stock Photos:** https://unsplash.com/

---

**Happy customizing! You've got this! 🎉**
