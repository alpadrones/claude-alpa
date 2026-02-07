# ALPA Systems — Website

Corporate website for ALPA Systems, a Spanish defense & unmanned systems company.

## 🚀 Deploy to Vercel

### Option 1: GitHub + Vercel (recommended)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/alpa-systems.git
   git push -u origin main
   ```

2. **Connect to Vercel:**
   - Go to [vercel.com](https://vercel.com) and sign in with GitHub
   - Click **"Add New → Project"**
   - Select the `alpa-systems` repository
   - Framework Preset: **Other**
   - Click **Deploy**
   - Done! Your site is live.

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

## 📁 Structure

```
alpa-systems/
├── index.html    ← Full website (single file)
└── README.md     ← This file
```

## 🖼️ Adding Images

Replace placeholder slots in `index.html` by finding `SLOT X` comments and replacing the placeholder `<div>` with your `<img>` or `<video>` tags.

## 📝 License

© 2026 ALPA Systems. All rights reserved.
