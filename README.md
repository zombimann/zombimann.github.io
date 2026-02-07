# Professional Portfolio Website

A clean, responsive portfolio website for Joseph Mugambi Ndwiga, showcasing software engineering, DevOps, and AI/ML expertise.


## 🌐 Live Demo
**Website:** [https://zombimann.github.io](https://zombimann.github.io)
**Website:** [Zoom Bee Apps](zombimann.pythonanywhere.com)

## 📋 Features

- **Fully Responsive Design** - Works on mobile, tablet, and desktop
- **Modern UI/UX** - Clean, professional interface with interactive elements
- **Fast Loading** - Lightweight and optimized for performance
- **Print-Friendly** - Optimized for printing CVs directly
- **Accessibility** - Semantic HTML and proper ARIA labels
- **Cross-Browser Compatible** - Works on all modern browsers

## 🚀 Quick Deployment

### Option 1: One-Click Fork & Deploy
1. **Fork this repository** to your GitHub account
2. **Rename the repository** to `[your-username].github.io`
3. **Wait 1-2 minutes** - GitHub Pages auto-deploys
4. **Visit** `https://[your-username].github.io`

### Option 2: Manual Setup
```bash
# Clone the repository
git clone https://github.com/zombimann/zombimann.github.io.git

# Navigate to folder
cd zombimann.github.io

# Open in browser (for local testing)
open index.html
```

## 📁 Project Structure
```
zombimann.github.io/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── README.md           # This documentation
│
├── assets/             # Optional assets folder
│   ├── images/         # Portfolio images
│   └── pdf/            # Downloadable CV
│
└── .nojekyll           # Optional: Disable Jekyll processing
```

## 🔧 Customization Guide

### 1. Update Personal Information
Edit `index.html` and replace:
- Name, title, and tagline (lines 23-25)
- Contact information (lines 29-36)
- Experience details (lines 78-135)
- Education and certifications (lines 149-166)

### 2. Change Color Scheme
In `style.css`, modify these CSS variables:
```css
:root {
    --primary-color: #4a6fa5;
    --secondary-color: #2c3e50;
    --accent-color: #3498db;
    --background-light: #f8f9fa;
}
```

### 3. Add Projects
Add more project cards in the Projects section:
```html
<div class="project-item">
    <h4>Project Title</h4>
    <p>Project description here</p>
    <a href="#" class="project-link">View Details →</a>
</div>
```

### 4. Add Images
1. Place images in `/assets/images/`
2. Update image paths in HTML:
```html
<img src="assets/images/profile.jpg" alt="Profile Picture">
```

## 🌈 Available Sections

| Section | Description | Editable |
|---------|-------------|----------|
| **Header** | Name, title, contact info | ✓ |
| **Summary** | Professional overview | ✓ |
| **Core Skills** | Technical skills organized by category | ✓ |
| **Experience** | Work history with details | ✓ |
| **Education** | Academic background | ✓ |
| **Certifications** | Professional certifications | ✓ |
| **Projects** | Highlighted projects | ✓ |
| **Additional Skills** | Soft skills and tools | ✓ |

## 📱 Mobile Responsive

The site automatically adjusts for:
- **Mobile** (< 480px): Single column layout
- **Tablet** (480px - 900px): Adaptive columns
- **Desktop** (> 900px): Full multi-column layout

## 🛠️ Development

### Local Development Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js with http-server
npx http-server

# Using PHP
php -S localhost:8000
```

### Testing
- Open Chrome DevTools (F12) for responsive testing
- Use Lighthouse for performance auditing
- Validate HTML at [validator.w3.org](https://validator.w3.org)

## 📝 License & Attribution

This portfolio template is open-source and available under the **MIT License**.

### Credits
- **Fonts**: [Google Fonts](https://fonts.google.com/) - Poppins & Roboto Mono
- **Icons**: [Font Awesome](https://fontawesome.com/) v6.4.0
- **Colors**: Custom palette designed for readability
- **Design**: Original design by Joseph Mugambi

### You are free to:
- Use for personal and commercial projects
- Modify and distribute
- Use privately

### You must:
- Maintain the original copyright notice
- Include the same license in derivatives

## 🔄 Updates & Maintenance

### Keeping the Site Updated
1. **Edit online**: Use GitHub's web editor
2. **Edit locally**: Clone and push changes
3. **Automatic deployment**: Changes deploy automatically to GitHub Pages

### Version History
- **v1.0** (Current): Initial portfolio launch
- Planned: Project gallery, blog integration, dark mode

## 🚨 Troubleshooting

### Common Issues & Solutions:

| Issue | Solution |
|-------|----------|
| Site not updating | Wait 2-3 minutes for GitHub Pages |
| 404 Error | Check repository name is `[username].github.io` |
| Styling broken | Clear browser cache (Ctrl+F5) |
| Images not loading | Check file paths and names |
| Mobile issues | Check viewport meta tag |

### GitHub Pages Status
- Check deployment at: `https://github.com/zombimann/zombimann.github.io/deployments`
- View build logs in: Settings → Pages → Build workflow

## 📬 Contact & Support

For issues with this template:
- **GitHub Issues**: [Create an issue](https://github.com/zombimann/zombimann.github.io/issues)
- **Email**: mugambindwiga@gmail.com
- **LinkedIn**: [linkedin.com/in/mugambi-n](https://linkedin.com/in/mugambi-n)

## 🌟 Features to Add (Future)

- [ ] Dark/Light mode toggle
- [ ] Project filtering by category
- [ ] Blog integration
- [ ] Contact form with backend
- [ ] Analytics integration
- [ ] PDF CV download
- [ ] Multi-language support

---

**Made with ❤️ by Joseph Mugambi Ndwigia**  
*Software Engineer & DevOps Practitioner*  
*Last Updated: February 2024*

---

## ⚡ Quick Commands

```bash
# Clone and deploy your own version
git clone https://github.com/zombimann/zombimann.github.io.git
cd zombimann.github.io
# Edit files, then:
git add .
git commit -m "Update portfolio"
git push origin main
```

Your site will be live at `https://zombimann.github.io` within 2 minutes!
