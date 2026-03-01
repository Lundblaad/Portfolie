# Quick Start Guide

## What's Been Created

Your portfolio website is ready! Here's what you have:

✅ `index.html` - Main "My Work" page with featured video and project grid
✅ `about.html` - "Om Adam Lundblad" page with your bio (from AdamInfo.txt)
✅ `styles.css` - Modern dark theme with smooth animations
✅ `assets/` folder - Ready for your media files

## Next Steps

### 1. Add Your Media Files

Copy these files into the `assets/` folder:

- `TheHypeReel.mp4` - Your video (required)
- `IMG_4911.JPG` - Your profile picture (required)
- Two PNG files for projects - name them `project-1.png` and `project-2.png`

### 2. Customize Project Descriptions

In `index.html`, update the project titles and descriptions:

```html
<h3>Project One</h3>
<p>Your project description here</p>
```

### 3. Update Skills (Optional)

In `about.html`, modify the skills list to match your actual competencies.

### 4. Deploy to GitHub Pages

```bash
cd "C:\Users\adams\Documents\GitHub\Portfolie"

git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git
git push -u origin main
```

Your site will be live at: `https://<your-username>.github.io`
