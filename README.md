# Aswin Raj Gowri Karthikeyan - Portfolio Website

A professional portfolio website showcasing work experience, projects, education, skills, and achievements.

## 📁 Files Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive functionality
├── images/             # Image assets
│   ├── hero-background.png
│   ├── paydart.png
│   └── profile.png
└── README.md          # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top-right corner
3. Select "New repository"
4. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is `aswinraj`, name it `aswinraj.github.io`
5. Make it **Public**
6. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `images` folder (with all images inside)
3. Scroll down and click "Commit changes"

**Option B: Using Git Commands**

```bash
# Clone your repository
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io

# Copy all portfolio files to this folder
# (Copy index.html, styles.css, script.js, and images folder)

# Add all files
git add .

# Commit the changes
git commit -m "Initial portfolio website"

# Push to GitHub
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and `/ (root)`
6. Click "Save"

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://your-username.github.io
```

## 🎨 Customization

### Update Personal Information

Edit `index.html` and update:
- Social media links (GitHub, LinkedIn)
- Download CV button link
- Any other personal details

### Change Colors

Edit `styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #10b981;  /* Change main accent color */
    --bg-primary: #0a0f14;     /* Change background color */
    /* ... other colors ... */
}
```

### Add More Projects

In `index.html`, find the Projects section and duplicate the `.project-card` div to add more projects.

### Update Images

Replace images in the `images/` folder:
- `hero-background.png` - Hero section background
- `paydart.png` - Project thumbnail
- `profile.png` - Your profile picture

## 📱 Features

- ✅ Responsive design (works on all devices)
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly menu
- ✅ Professional animations
- ✅ SEO optimized
- ✅ Fast loading

## 🔧 Troubleshooting

**Images not showing?**
- Make sure the `images` folder is uploaded with all images
- Check that image filenames match exactly (case-sensitive)

**Website not appearing?**
- Wait 5-10 minutes after pushing to GitHub
- Make sure GitHub Pages is enabled in repository settings
- Check that repository name is `your-username.github.io`

**Styling looks broken?**
- Ensure `styles.css` is in the same folder as `index.html`
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)

## 📝 License

© 2025 Aswin Raj Gowri Karthikeyan. All rights reserved.

## 🤝 Support

For any issues or questions, feel free to open an issue on GitHub.
