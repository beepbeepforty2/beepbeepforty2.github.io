# Pratik Chatse - Resume Website

A minimalist, modern resume website built for GitHub Pages deployment. Features SEO optimization, ATS-friendly structure, and responsive design.

## Features

- Clean, minimalist design with professional typography
- Fully responsive (mobile, tablet, desktop)
- SEO-optimized with meta tags and JSON-LD structured data
- ATS-friendly HTML structure
- Print-friendly CSS styling
- Fast loading with no external dependencies
- Jekyll-ready for GitHub Pages

## Quick Start

### Local Development

1. Clone this repository
2. Open `index.html` in your browser to preview locally

### GitHub Pages Deployment

#### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub named `pratikchatse.github.io` (replace with your username)
2. Upload all files from this directory to the repository
3. Go to repository Settings > Pages
4. Under "Source", select the `main` branch
5. Click "Save"
6. Your site will be live at `https://pratikchatse.github.io` in a few minutes

#### Method 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Resume website"

# Add remote repository (replace with your GitHub username)
git remote add origin https://github.com/pratikchatse/pratikchatse.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Method 3: Deploy to a Project Page

If you want to deploy to a project repository (e.g., `https://yourusername.github.io/resume`):

1. Create a new repository with any name (e.g., `resume`)
2. Upload files or push using git
3. Go to Settings > Pages
4. Select the `main` branch as source
5. Your site will be live at `https://yourusername.github.io/resume`
6. Update the `baseurl` in `_config.yml` to `/resume`

## Customization

### Update Content

Edit `index.html` to update:
- Personal information in the header
- Summary section
- Skills
- Professional experience
- Projects
- Education

### Update Site Configuration

Edit `_config.yml` to update:
- Site title and description
- URL settings
- SEO information
- Social media links

### Styling

All styles are contained within `index.html` in the `<style>` section. Key CSS variables are defined in `:root` for easy color scheme customization:

```css
:root {
    --primary-dark: #1a2332;
    --text-dark: #2d3748;
    --text-medium: #4a5568;
    --text-light: #718096;
    --border-color: #e2e8f0;
    --accent-blue: #2b6cb0;
}
```

## File Structure

```
resume_website/
├── index.html          # Main resume page
├── _config.yml         # Jekyll configuration
└── README.md           # This file
```

## SEO Features

- Semantic HTML5 structure
- Meta description and keywords
- Open Graph tags for social media
- JSON-LD structured data for search engines
- Proper heading hierarchy (H1-H4)
- Alt text ready for images

## ATS-Friendly Features

- Semantic HTML tags (header, main, section, article)
- Clear heading hierarchy
- Easy text selection and copy-paste
- No complex layouts that confuse parsers
- Standard font families

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Print Support

The resume includes print-optimized CSS that automatically formats the page for printing or PDF export. Use your browser's print function (Ctrl+P or Cmd+P) to generate a PDF.

## License

This project is open source and available for personal use.

## Contact

For questions or feedback, please visit the GitHub repository or contact through the information provided on the resume.

---

Built with HTML, CSS, and Jekyll for GitHub Pages
