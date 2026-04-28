# BetterPlanet Website - Deployment Guide

## ✅ Build Complete!

All 5 pages are built, fully functional, and ready for deployment to GitHub Pages.

### What's Been Built

**5 Complete Pages:**
- ✅ index.html (Home - Landing page with hero, tools preview, 11 pillars)
- ✅ tv.html (BetterPlanet TV - 37 YouTube videos in 11 categories, filterable)
- ✅ about.html (About organization and founder)
- ✅ get-involved.html (Partnership tiers and contact form)
- ✅ tools.html (3 interactive wellbeing tools with localStorage)

**Design System:**
- ✅ styles.css (Complete design system with color variables, animations, responsive grid)
- ✅ script.js (Mobile menu, typewriter effect, localStorage utilities)

**Documentation:**
- ✅ README.md (Project overview)
- ✅ PROGRESS.md (Detailed build progress)
- ✅ .gitignore (Standard Node/IDE ignores)

---

## 🚀 Next Steps: Push to GitHub

### Step 1: Ensure GitHub Repository Exists

Create the repository on GitHub if it doesn't exist:
1. Go to https://github.com/new
2. Repository name: `betterplanetcoop.github.io`
3. Make it **Public**
4. Leave "Initialize this repository with" unchecked (we'll push our existing repo)
5. Click "Create repository"

### Step 2: Add Remote and Push

Run these commands in your terminal (from `c:\Users\Martinez\BetterPlanetCoop`):

```powershell
# Add the GitHub repository as remote
git remote add origin https://github.com/betterplanetcoop/betterplanetcoop.github.io.git

# Verify remote is added
git remote -v

# Push to GitHub
git push -u origin main
```

**Note:** If the default branch is "master" instead of "main":
```powershell
git push -u origin master
```

### Step 3: Enable GitHub Pages

1. Go to https://github.com/betterplanetcoop/betterplanetcoop.github.io
2. Click **Settings** (gear icon)
3. In the left sidebar, click **Pages**
4. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **main** (or **master**)
   - Folder: Select **/ (root)**
5. Click **Save**

GitHub will show: "Your site is live at https://betterplanetcoop.github.io"

### Step 4: Verify Live Site

- Open https://betterplanetcoop.github.io in your browser
- Test all navigation links
- Test all interactive features (video filtering, tools)
- Test mobile responsiveness

---

## 🔍 What to Test After Deployment

- [ ] Home page loads with animated hero
- [ ] Typewriter effect cycles through 3 phrases
- [ ] All navigation links work across pages
- [ ] Mobile hamburger menu works
- [ ] TV page videos load and play
- [ ] Video filters work correctly
- [ ] Tools persist data in browser
- [ ] Gratitude Journal saves/deletes entries
- [ ] Thank You Notes templates load and copy works
- [ ] MeTime Scheduler allows scheduling
- [ ] Forms and links to external sites work
- [ ] Responsive design on mobile/tablet

---

## 📊 File Structure

```
betterplanetcoop/
├── index.html              (Home page)
├── tv.html                 (Video gallery)
├── about.html              (About organization)
├── get-involved.html       (Partnerships)
├── tools.html              (Interactive tools)
├── styles.css              (Design system)
├── script.js               (Shared utilities)
├── README.md               (Project overview)
├── PROGRESS.md             (Build progress)
├── DEPLOYMENT.md           (This file)
└── .gitignore              (Git ignore file)
```

---

## 🆘 Troubleshooting

**Remote already exists?**
```powershell
git remote remove origin
git remote add origin https://github.com/betterplanetcoop/betterplanetcoop.github.io.git
```

**Wrong branch?**
```powershell
git branch -M main
git push -u origin main
```

**Pages still not showing?**
- Wait 1-2 minutes for GitHub to deploy
- Check Settings > Pages to confirm source is set correctly
- Clear browser cache or try incognito window

---

## 📝 Making Updates After Deployment

To make changes and push them live:

```powershell
# Make your changes in the files

# Stage changes
git add .

# Commit with a message
git commit -m "Description of changes"

# Push to GitHub
git push
```

The site will update automatically within seconds.

---

## 🎉 You're All Set!

The BetterPlanet Co-op website is ready for the world to see. The combination of warm design, interactive tools, and mission-driven content creates a unique digital experience that aligns perfectly with the organization's values.

**Live at:** https://betterplanetcoop.github.io

---

Built with ❤️ for a better planet.
Contact: nicole@betterplanet.org
