# Simple Portfolio Website

A clean, modern portfolio website with minimal animations built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Minimal Animations**: Subtle animations that enhance user experience without being overwhelming
- **Modern UI**: Clean and professional design with smooth transitions
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices

## Sections

1. **Hero Section**: Introduction with animated typing effect
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills with hover effects
4. **Projects Section**: Featured projects with links
5. **Contact Section**: Contact form and social links

## Customization Guide

### Personal Information

1. **Name and Title**: Update in `index.html`
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <p class="hero-subtitle">Full Stack Developer & Designer</p>
   ```

2. **About Section**: Modify the text in the about section
   ```html
   <p>I'm a passionate developer with a love for creating innovative solutions...</p>
   ```

3. **Statistics**: Update the numbers in the about section
   ```html
   <div class="stat">
       <h3>3+</h3>
       <p>Years Experience</p>
   </div>
   ```

### Skills

Update the skills section by modifying the skill cards:
```html
<div class="skill-card">
    <i class="fab fa-html5"></i>
    <h3>HTML5</h3>
    <p>Semantic markup and accessibility</p>
</div>
```

### Projects

Replace the project cards with your own projects:
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

### Contact Information

Update contact details in the contact section:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

### Social Links

Update social media links:
```html
<div class="social-links">
    <a href="#" class="social-link"><i class="fab fa-github"></i></a>
    <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## Color Scheme

The current color scheme uses:
- Primary Blue: `#2563eb`
- Secondary Blue: `#1d4ed8`
- Yellow Accent: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

To change colors, update the CSS variables in `styles.css`.

## Animations

The website includes minimal animations:
- Fade-in effects on scroll
- Hover effects on cards and buttons
- Typing effect on hero title
- Smooth transitions
- Ripple effect on button clicks

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## How to Use

1. **Open the website**: Double-click `index.html` or open it in a web browser
2. **Customize content**: Edit the HTML file to update your information
3. **Modify styling**: Update `styles.css` to change colors, fonts, or layout
4. **Add functionality**: Modify `script.js` for additional features

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance

The website is optimized for:
- Fast loading times
- Smooth animations
- Mobile responsiveness
- SEO-friendly structure

## Tips for Customization

1. **Add your photo**: Replace the profile placeholder with your actual image
2. **Update projects**: Add real project screenshots and links
3. **Customize colors**: Match your personal brand colors
4. **Add more sections**: Include testimonials, blog, or services sections
5. **Integrate with backend**: Connect the contact form to a real email service

## License

This project is open source and available under the MIT License.

---

**Note**: Remember to replace all placeholder content with your actual information before publishing your portfolio! "# .portfolio" 
