# Fahrul Sanjaya - Portfolio Website

Neo-brutalist portfolio website showcasing full-stack development projects.

## 🚀 Live Site

[https://buildwithjay.me](https://buildwithjay.me)

## 📂 Project Structure

```
portfolio/
├── index.html              # Main portfolio homepage
├── project.html            # Template for project detail pages
├── ecommerce-platform.html # Example project detail page
└── README.md              # This file
```

## 🎨 Features

- **Neo-Brutalist Design**: Bold borders, high contrast, raw aesthetic
- **Fully Responsive**: Mobile-first design approach
- **Accessible**: WCAG AA compliant with proper ARIA labels
- **Zero Dependencies**: Pure HTML/CSS/JS with Tailwind via CDN
- **Fast Performance**: Optimized loading with minimal overhead

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Google Fonts** - Space Grotesk & Material Symbols
- **Vanilla JS** - No frameworks, pure JavaScript

## 📝 Adding New Projects

1. Copy `project.html` template:
   ```bash
   cp project.html your-new-project.html
   ```

2. Update the file with your project details:
   - Meta tags (title, description)
   - Hero section (project name, description, tech stack)
   - Key features (add/remove/modify feature cards)
   - Live demo links (update URLs)
   - Screenshots (replace placeholders)

3. Link from homepage in `index.html`:
   ```html
   <a href="your-new-project.html" class="...">
   ```

## 🚀 Deployment

### GitHub Pages

1. Push to GitHub repository
2. Go to Settings → Pages
3. Source: Deploy from a branch
4. Branch: `main` / `root`
5. Save - your site will be live at `https://username.github.io/repository-name`

### Vercel/Netlify

Simply connect your GitHub repository - they auto-detect static sites.

## 🎨 Customization

### Colors

Edit the Tailwind config in the `<script>` tag:

```javascript
colors: {
    "primary": "#0d7ff2",        // Blue
    "accent-yellow": "#E2F700",  // Yellow
    "accent-pink": "#FF006E",    // Pink
    "accent-green": "#39FF14",   // Green
    // ... add more colors
}
```

### Fonts

Currently using **Space Grotesk** for headings and body text. Change in the Google Fonts link.

---

**Made with ❤️ in Surabaya, Indonesia**
© 2020 Fahrul Sanjaya
