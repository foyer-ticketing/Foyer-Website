# Foyer Website

A modern, responsive website for the Foyer app built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Customizable Branding**: Easy-to-update color scheme and fonts
- **Fast Loading**: Optimized for performance
- **SEO Ready**: Semantic HTML structure and meta tags
- **Contact Form**: Functional contact form with validation

## 📁 Project Structure

```
Foyer-Website/
├── index.html              # Main HTML file
├── styles.css              # CSS styles and responsive design
├── script.js               # JavaScript functionality
├── assets/
│   ├── images/             # Images and logos
│   │   ├── logo.svg        # Your Foyer logo (SVG recommended)
│   │   ├── hero-image.png  # Hero section image
│   │   ├── about-image.png # About section image
│   │   └── favicon.ico     # Website favicon
│   └── icons/              # Additional icons
└── README.md               # This file
```

## 🎨 Customization

### Brand Colors
Update the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #6366f1;    /* Your primary brand color */
    --secondary-color: #10b981;  /* Your secondary brand color */
    /* ... other colors */
}
```

### Typography
Replace the Google Fonts link in `index.html` with your custom fonts:

```html
<!-- Replace this line -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Content
Edit the content in `index.html`:
- Update the title and meta description
- Replace placeholder text with your actual content
- Add your real contact information
- Update feature descriptions

### Images
Add your images to the `assets/images/` folder:
- `logo.svg` - Your Foyer logo
- `hero-image.png` - App screenshot or hero image
- `about-image.png` - About section image
- `favicon.ico` - Website icon

## 🛠️ Setup Instructions

1. **Clone or download** this repository
2. **Add your assets**:
   - Place your logo in `assets/images/logo.svg`
   - Add hero image as `assets/images/hero-image.png`
   - Add about image as `assets/images/about-image.png`
   - Add favicon as `assets/images/favicon.ico`

3. **Customize the content**:
   - Edit `index.html` to update text content
   - Modify colors in `styles.css` CSS custom properties
   - Update contact information and social links

4. **Test locally**:
   - Open `index.html` in your web browser
   - Test on different screen sizes
   - Verify all links and forms work

5. **Deploy**:
   - Upload all files to your web server
   - Ensure all file paths are correct
   - Test the live site

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🎯 Sections

- **Navigation**: Fixed header with smooth scrolling
- **Hero**: Main landing section with call-to-action
- **Features**: Three-column feature showcase
- **About**: Story and information about Foyer
- **Contact**: Contact form and information
- **Footer**: Links and copyright

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📞 Contact Form

The contact form includes:
- Name validation
- Email validation
- Message validation
- Success/error feedback

**Note**: The form currently shows a success message. To make it functional, you'll need to:
1. Set up a backend service to handle form submissions
2. Update the JavaScript in `script.js` to send data to your server
3. Consider using services like Formspree, Netlify Forms, or similar

## 🚀 Performance Tips

- Optimize images (use WebP format when possible)
- Minify CSS and JavaScript for production
- Enable gzip compression on your server
- Use a CDN for faster loading

## 📄 License

This project is open source and available under the MIT License.

---

**Need help?** Feel free to reach out if you need assistance customizing or deploying your Foyer website!