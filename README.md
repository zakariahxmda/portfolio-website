# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, interactive elements, and a professional design perfect for showcasing your work and skills.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with gradient accents and smooth animations
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Hero Section**: Eye-catching introduction with call-to-action buttons and social links
- **About Section**: Personal information and background
- **Skills Section**: Organized display of technical skills and technologies
- **Projects Portfolio**: Showcase of your work with hover effects and project details
- **Contact Form**: Functional contact form with validation and notifications
- **Animations**: Fade-in effects, parallax scrolling, and micro-interactions
- **SEO Optimized**: Semantic HTML5 structure and meta tags

## Quick Start

1. **Clone or download** the project files
2. **Open `index.html`** in your browser or
3. **Run a local server**:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Visit** `http://localhost:8000` in your browser

## Customization

### Personal Information

Update the following in `index.html`:

```html
<!-- Navigation Logo -->
<h3>Your Name</h3>

<!-- Hero Section -->
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Title | Your Expertise | Your Passion</p>

<!-- About Section -->
<div class="info-item">
    <span class="info-label">Name:</span>
    <span class="info-value">Your Name</span>
</div>
<div class="info-item">
    <span class="info-label">Email:</span>
    <span class="info-value">your.email@example.com</span>
</div>
<div class="info-item">
    <span class="info-label">Location:</span>
    <span class="info-value">Your City, Country</span>
</div>
```

### Profile Image

Replace the placeholder image in the hero section:

```html
<div class="profile-img">
    <img src="your-image.jpg" alt="Profile">
</div>
```

### Social Links

Update all social media links throughout the file:

```html
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
<a href="https://linkedin.com/in/yourusername" class="social-link">
    <i class="fab fa-linkedin"></i>
</a>
```

### Skills

Modify the skills section in `index.html`:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>Your Skill</span>
</div>
```

### Projects

Update project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-screenshot.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="https://yourproject.com" class="project-link">
                    <i class="fas fa-eye"></i> View
                </a>
                <a href="https://github.com/yourusername/project" class="project-link">
                    <i class="fab fa-github"></i> Code
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
            <span class="tag">Framework</span>
        </div>
    </div>
</div>
```

### Contact Form

The contact form is ready to use. To make it functional, you'll need to:

1. **Option 1**: Integrate with a form service like Formspree, Netlify Forms, or EmailJS
2. **Option 2**: Create a backend endpoint to handle form submissions
3. **Option 3**: Use the current JavaScript validation and display a message

Example with Formspree:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields remain the same -->
</form>
```

### Colors and Styling

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #667eea;    /* Main brand color */
    --secondary-color: #764ba2;  /* Secondary brand color */
    --accent-color: #f093fb;     /* Accent color */
    --text-dark: #2d3748;        /* Main text color */
    --text-light: #718096;       /* Secondary text color */
    --bg-light: #f7fafc;         /* Light background */
    --bg-white: #ffffff;         /* White background */
}
```

### Typography

Change fonts by updating the Google Fonts link in `index.html` and the font-family in `styles.css`:

```html
<!-- In index.html head -->
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

```css
/* In styles.css */
body {
    font-family: 'YourFont', sans-serif;
}
```

## File Structure

```
portfolio-website/
|-- index.html          # Main HTML file
|-- styles.css          # All styles and animations
|-- script.js           # Interactive JavaScript functionality
|-- README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized animations using CSS transforms
- Debounced scroll events for better performance
- Lazy loading ready for images
- Minimal dependencies (only Font Awesome icons)

## Additional Features You Can Add

1. **Blog Section**: Add a blog or articles section
2. **Testimonials**: Client testimonials and recommendations
3. **Resume Download**: Add a downloadable resume button
4. **Dark Mode**: Implement a dark/light theme toggle
5. **Analytics**: Add Google Analytics or similar
6. **SEO**: Enhance with more meta tags and structured data

## Deployment

### Netlify
1. Push to GitHub
2. Connect repository to Netlify
3. Deploy automatically

### Vercel
1. Push to GitHub
2. Import project to Vercel
3. Deploy with one click

### GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Select main branch as source

## Support

This portfolio is built with modern web standards and best practices. If you encounter any issues or need help with customization, feel free to reach out or consult the code comments.

## License

This project is open source and available under the [MIT License](LICENSE).
