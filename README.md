# Game Developer Portfolio

A modern, responsive portfolio website for game developers built with HTML, CSS, and JavaScript.

## Features

- 🎮 Game developer focused design
- 📱 Fully responsive layout
- 🎨 Modern UI with smooth animations
- 🚀 Fast loading and optimized
- 💼 Showcase your games and projects
- 🛠️ Skills and technologies section
- 📧 Contact form ready

## Deployment Options

### Option 1: GitHub Pages (Recommended)

Since your repository is named `McRobert812.github.io`, it's perfect for GitHub Pages:

1. **Initialize Git repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Game Developer Portfolio"
   ```

2. **Create repository on GitHub**:
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it exactly: `McRobert812.github.io`
   - Make it public (required for free GitHub Pages)

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/McRobert812/McRobert812.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under **Source**, select `main` branch
   - Click **Save**
   - Your site will be live at: `https://mcrobert812.github.io`

### Option 2: Netlify

1. Go to [Netlify](https://www.netlify.com)
2. Sign up/login
3. Drag and drop your project folder, OR
4. Connect your GitHub repository for automatic deployments
5. Your site will be live instantly with a free `.netlify.app` domain

### Option 3: Vercel

1. Go to [Vercel](https://vercel.com)
2. Sign up/login
3. Import your GitHub repository, OR
4. Deploy via Vercel CLI:
   ```bash
   npm i -g vercel
   vercel
   ```

### Option 4: Traditional Web Hosting

Upload all files via FTP/SFTP to your web hosting provider:
- Upload all files maintaining the folder structure
- Ensure `index.html` is in the root directory
- Your site will be accessible via your domain

## Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Customization

Before deploying, make sure to:

1. **Update social media links** in `index.html` and `contact.html`:
   - Replace placeholder URLs with your actual profiles
   - Update GitHub, LinkedIn, Steam, Twitter, YouTube links

2. **Update contact information** in `contact.html`:
   - Update address, phone, and email

3. **Add your resume**:
   - Replace `RobertLawhead.pdf` with your actual resume file
   - Update the link in the footer

4. **Update images**:
   - Replace placeholder images in `img/` folder with your own
   - Update hero images, about images, etc.

5. **Update project links**:
   - Update all game project links in the Work section
   - Ensure GitHub, Steam, and Play Store links are correct

## File Structure

```
.
├── index.html          # Main homepage
├── contact.html        # Contact page
├── css/               # Stylesheets
├── js/                # JavaScript files
├── img/               # Images and assets
├── fonts/             # Font files
└── sass/              # SASS source files (optional)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This template is free to use for personal and commercial projects.

---

**Need help?** Check the deployment documentation for your chosen platform or open an issue on GitHub.
