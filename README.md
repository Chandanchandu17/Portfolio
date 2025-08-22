# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a sleek dark/light mode toggle, smooth animations, and a professional layout perfect for showcasing your skills and projects.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that looks great on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with preference saving
- **Smooth Animations**: Engaging scroll animations and hover effects
- **Interactive Navigation**: Active link highlighting and smooth scrolling
- **Modern UI/UX**: Clean, professional design with card-based layouts
- **Contact Form**: Functional contact form (ready for backend integration)
- **Skills Showcase**: Organized display of technical skills with icons
- **Project Gallery**: Responsive grid layout for project showcase
- **Timeline**: Interactive education and experience timeline
- **Testimonials**: Auto-rotating testimonial slider

## 🖥️ Demo

[Live Demo](https://your-username.github.io/portfolio) *(Replace with your actual GitHub Pages URL)*

## 📱 Screenshots

### Light Mode
![Light Mode](screenshots/light-mode.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   live-server
   ```

3. **Customize the content**
   - Update personal information in `index.html`
   - Replace placeholder images with your own
   - Modify colors and styling in `styles.css`
   - Add your projects, skills, and experience

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling and themes
├── script.js           # JavaScript functionality
├── README.md           # This file
├── images/             # Your images folder (create this)
│   ├── profile.jpg
│   ├── project1.png
│   └── ...
└── screenshots/        # Screenshots for README (optional)
    ├── light-mode.png
    └── dark-mode.png
```

## 🛠️ Customization

### Personal Information
Update the following in `index.html`:
- Name and title in the hero section
- About me content
- Contact information
- Social media links
- Profile images

### Skills
Modify the skills section to include your technologies:
```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <h4>Your Skill</h4>
    <p>Skill Level</p>
</div>
```

### Projects
Add your projects in the projects section:
```html
<div class="project-card">
    <div class="project-img">
        <img src="path-to-your-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="project-links">
            <a href="github-link" class="btn btn-sm">GitHub</a>
            <a href="live-demo-link" class="btn btn-sm">Live Demo</a>
        </div>
    </div>
</div>
```

### Color Theme
Customize colors in `styles.css`:
```css
:root {
    --primary-color: #6ebe3b;    /* Your brand color */
    --background-color: #f5f5f5; /* Light background */
    --text-color: #333;          /* Text color */
    /* ... other variables */
}
```

## 🎨 Icons

This project uses Font Awesome icons. You can find more icons at:
- [Font Awesome Icons](https://fontawesome.com/icons)
- [Font Awesome Brands](https://fontawesome.com/icons?d=gallery&s=brands)

## 📧 Contact Form Integration

The contact form is ready for backend integration. Popular options include:

### Netlify Forms (Recommended for static hosting)
Add `netlify` attribute to your form:
```html
<form class="contact-form" netlify>
```

### Formspree
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

### EmailJS
For client-side email sending without a backend server.

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main` or `gh-pages`)
4. Your site will be available at `https://your-username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy with default settings
3. Get a custom domain or use the provided netlify.app subdomain

### Vercel
1. Import your GitHub repository to Vercel
2. Deploy with default settings
3. Get a custom domain or use the provided vercel.app subdomain

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)


## 🙏 Acknowledgments

- Font Awesome for the beautiful icons
- Google Fonts for typography
- CSS Grid and Flexbox for modern layouts
- Inspiration from modern portfolio designs

---

⭐ **Star this repository if you found it helpful!**

