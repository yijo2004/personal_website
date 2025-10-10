# Personal Website Template

A modern, responsive personal website template built with HTML, CSS, and JavaScript. Perfect for developers, designers, or anyone looking to showcase their work and skills.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **Accessible**: Built with accessibility best practices
- **Easy to Customize**: Well-organized code with clear comments

## 📁 File Structure

```
personal_website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Sections Included

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Portfolio showcase with project cards
5. **Contact Section**: Contact form and social media links
6. **Navigation**: Fixed navigation bar with smooth scrolling

## 🛠️ Customization Guide

### 1. Personal Information

#### Update Your Name and Title
In `index.html`, replace the following:
```html
<title>Your Name - Personal Website</title>
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">A passionate developer creating amazing digital experiences</p>
```

#### Update About Section
Modify the about text in the About section:
```html
<p>I'm a passionate developer with a love for creating innovative solutions...</p>
```

#### Update Contact Information
Replace the contact details:
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### 2. Skills Section

Update the skills in `index.html`:
```html
<div class="skill-category">
    <h3>Frontend Development</h3>
    <div class="skill-items">
        <span class="skill-item">HTML5</span>
        <span class="skill-item">CSS3</span>
        <!-- Add your skills here -->
    </div>
</div>
```

### 3. Projects Section

Replace the example projects with your own:
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-url" class="project-link">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

### 4. Profile Image

Replace the placeholder icon with your actual profile image:
```html
<div class="profile-image">
    <img src="path/to/your/profile-image.jpg" alt="Your Name">
</div>
```

### 5. Social Media Links

Update the social media links in the contact section:
```html
<a href="your-github-url" class="social-link">
    <i class="fab fa-github"></i>
</a>
<a href="your-linkedin-url" class="social-link">
    <i class="fab fa-linkedin"></i>
</a>
```

### 6. Color Scheme

To change the color scheme, update the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --secondary-color: #fbbf24;  /* Accent yellow color */
    --text-color: #333;         /* Main text color */
    --bg-color: #ffffff;        /* Background color */
}
```

### 7. Statistics

Update the statistics in the About section:
```html
<div class="stat">
    <h3>5+</h3>
    <p>Years Experience</p>
</div>
```

## 🎯 Adding New Sections

To add a new section:

1. **Add HTML structure** in `index.html`:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content here -->
    </div>
</section>
```

2. **Add navigation link**:
```html
<a href="#new-section" class="nav-link">New Section</a>
```

3. **Add CSS styles** in `styles.css`:
```css
.new-section {
    padding: 80px 0;
    background: #f8fafc;
}
```

## 📱 Responsive Breakpoints

The website uses these breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 767px and below

## 🚀 Deployment

### Option 1: GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and save
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. You can connect to GitHub for automatic deployments

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 🔧 Advanced Customization

### Adding Animations
The website includes several animation classes:
- `.fade-in-up`: Slides content up with fade effect
- `.animate-in`: Bounce animation for skill items

### Form Handling
The contact form includes basic validation. To connect to a backend:
1. Update the form action in `index.html`
2. Modify the form submission handler in `script.js`

### SEO Optimization
- Update meta tags in the `<head>` section
- Add Open Graph tags for social media sharing
- Include structured data markup

## 📝 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you have any questions or need help customizing the website, feel free to:
- Open an issue on GitHub
- Contact me through the contact form on the website

---

**Happy coding! 🎉**
