# Personal Portfolio Website

A clean, professional portfolio website designed to showcase your skills and projects to potential employers.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Three Main Sections**: About, Projects, and Contact (fits within 3 scroll lengths as requested)
- **GitHub Integration Ready**: Easy to host on GitHub Pages
- **Fast Loading**: Optimized CSS and minimal JavaScript

## Customization Guide

### 1. Personal Information
Edit `index.html` and replace:
- `Your Name` with your actual name
- `your.email@example.com` with your email
- `yourusername` with your GitHub username
- `yourprofile` with your LinkedIn profile name

### 2. Projects Section
Update the project cards in `index.html`:
- Change project titles and descriptions
- Update GitHub repository links
- Modify tech stack tags to match your projects

### 3. Skills Section
In the About section, update the skill tags to reflect your expertise:
```html
<span class="skill-tag">Your Skill</span>
```

### 4. Colors and Styling
Modify `styles.css` to change:
- Primary color: Search for `#3498db` and replace with your preferred color
- Background gradients in the hero section
- Font families and sizes

## Deployment Options

### GitHub Pages (Recommended)

#### Option 1: Custom Repository Name
1. Create a new repository (e.g., `leander-portfolio` or `energy-finance-portfolio`)
2. Upload all files to the repository
3. **Rename `LeanderWeigelt.html` to `index.html`** (GitHub Pages looks for index.html)
4. Go to repository Settings → Pages
5. Select "Deploy from a branch" → "main" → "/ (root)"
6. Your site will be available at `https://yourusername.github.io/repository-name`

#### Option 2: Username Repository (Alternative)
1. Create a repository named exactly `yourusername.github.io`
2. Upload all files and rename `LeanderWeigelt.html` to `index.html`
3. Your site will be available at `https://yourusername.github.io`

### Alternative Hosting
- **Netlify**: Drag and drop the portfolio folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages with custom domain**: Add a CNAME file

## File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # This file
```

## Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Tips for Employers
- Keep project descriptions concise but impactful
- Include live demo links when possible
- Highlight technologies relevant to target positions
- Update regularly with new projects
- Ensure all links work before sharing

## Next Steps
1. Customize all placeholder content
2. Add your actual project repositories
3. Test on different devices
4. Deploy to GitHub Pages
5. Share the link on your resume and LinkedIn profile