# Adam Lundblad - Portfolio Website

A modern, dark-themed portfolio website showcasing creative work and professional profile.

## Website Structure

### Pages
- **index.html** - Main portfolio page ("My Work") featuring video and image projects
- **about.html** - Personal profile page ("Om Adam Lundblad")

### Styling
- **styles.css** - Modern dark theme with responsive design, smooth animations, and gradient effects

### Assets
- **assets/TheHypeReel.mp4** - Your main video reel (add this file)
- **assets/IMG_4911.JPG** - Your profile picture (add this file)
- **assets/project-1.png** - First project image (replace the placeholder)
- **assets/project-2.png** - Second project image (replace the placeholder)

## Setup Instructions

### Local Preview
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Navigate between pages using the navigation menu

### Deploy to GitHub Pages

1. Create a GitHub repository named `<username>.github.io`
2. Push all website files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git push -u origin main
   ```

3. Your website will be available at `https://<username>.github.io`

## Files to Add

Before deploying, make sure to add these files to the **assets** folder:

1. **TheHypeReel.mp4** - Your video file (MP4 format recommended)
2. **IMG_4911.JPG** - Your profile photo (JPG format)
3. Replace **project-1.png** and **project-2.png** with your actual project images

## Customize Content

### Main Page
- Edit the portfolio grid items in `index.html` to add descriptions
- Add more projects by duplicating the `.portfolio-item` div

### About Page
- The Swedish text is pulled from `AdamInfo.txt`
- Add or modify skills in the skills list
- Customize the competencies to match your actual skills

## Design Features

- **Dark Theme**: Sleek black and cyan color scheme
- **Responsive**: Fully responsive design for mobile, tablet, and desktop
- **Smooth Animations**: Hover effects and transitions for interactive elements
- **Modern Typography**: Clean, professional fonts with proper hierarchy
- **Gradient Accents**: Subtle gradient effects on headings and borders
- **Performance**: Lightweight CSS with no external dependencies

## Color Palette

- **Primary Background**: `#0f0f0f` (Almost black)
- **Secondary Background**: `#1a1a1a` (Dark gray)
- **Accent Color**: `#00d4ff` (Cyan blue)
- **Text Primary**: `#ffffff` (White)
- **Text Secondary**: `#b0b0b0` (Light gray)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

---

**Ready to go live!** Add your media files and deploy to GitHub Pages.
