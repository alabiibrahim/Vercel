# Alabi Ibrahim – Data Analyst Portfolio

A clean, professional, fully responsive portfolio website built for Vercel deployment.

## 🚀 Deploy to Vercel

### Option 1: Vercel CLI
```bash
npm install -g vercel
vercel
```

### Option 2: GitHub + Vercel Dashboard
1. Push this folder to a new GitHub repository
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click **"New Project"** → Import your GitHub repo
4. Leave all settings as default → Click **"Deploy"**
5. Your site will be live in ~60 seconds ✅

## 📁 File Structure
```
portfolio/
├── index.html      ← All-in-one portfolio (HTML + CSS + JS)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

## ✏️ Customizations
- **Profile photo**: Already pulls from your GitHub portfolio at `alabiibrahim.github.io/myportfolio/Pics4me.png`
- **Skills %**: Edit the `data-width` values on `.progress-fill` elements
- **Projects**: Add new `.project-card` divs inside `#panel-all`
- **Colors**: Change CSS variables at the top of `<style>` — `--red`, `--white`, etc.
- **Font**: Using Tahoma (system font), matches the Taoma aesthetic requested

## 🎨 Design Features
- Red & white color scheme with black text
- Tahoma font throughout
- Animated progress bars (scroll-triggered)
- Filterable project tabs by tool (Excel, Power BI, SQL, Python, Tableau)
- Mobile + desktop responsive
- Smooth scroll navigation
- Fixed header with hamburger menu on mobile
