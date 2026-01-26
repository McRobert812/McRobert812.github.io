# Deployment Guide

## Quick Start: GitHub Pages

### Step 1: Initialize Git (if not done)

Open terminal/command prompt in your project folder:

```bash
git init
```

### Step 2: Add All Files

```bash
git add .
git commit -m "Initial commit - Game Developer Portfolio"
```

### Step 3: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `McRobert812.github.io` (must match exactly)
3. Make it **Public** (required for free GitHub Pages)
4. **Don't** initialize with README, .gitignore, or license
5. Click "Create repository"

### Step 4: Connect and Push

```bash
git remote add origin https://github.com/McRobert812/McRobert812.github.io.git
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment
7. Your site will be live at: **https://mcrobert812.github.io**

## Alternative: Netlify (Easiest)

### Method 1: Drag & Drop

1. Go to https://app.netlify.com/drop
2. Drag your entire project folder
3. Done! You'll get a URL like `random-name.netlify.app`

### Method 2: GitHub Integration

1. Push your code to GitHub (follow steps above)
2. Go to https://app.netlify.com
3. Click "Add new site" → "Import an existing project"
4. Choose GitHub and select your repository
5. Click "Deploy site"
6. Every time you push to GitHub, Netlify auto-deploys!

### Custom Domain (Optional)

1. In Netlify dashboard, go to **Domain settings**
2. Click **Add custom domain**
3. Follow instructions to configure DNS

## Alternative: Vercel

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow prompts (defaults work fine)
4. Your site will be live instantly!

## Troubleshooting

### GitHub Pages Not Working?

- ✅ Repository must be **public**
- ✅ Repository name must be `username.github.io`
- ✅ Files must be in the `main` branch
- ✅ Wait 5-10 minutes after enabling Pages
- ✅ Check Settings → Pages for any errors

### Images Not Loading?

- Use **relative paths**: `img/logo.png` (not `/img/logo.png`)
- Ensure all image files are committed to Git
- Check file names match exactly (case-sensitive)

### CSS/JS Not Loading?

- Check browser console for 404 errors
- Verify file paths are correct
- Clear browser cache (Ctrl+F5)

### Need Help?

- GitHub Pages Docs: https://docs.github.com/pages
- Netlify Docs: https://docs.netlify.com
- Vercel Docs: https://vercel.com/docs
