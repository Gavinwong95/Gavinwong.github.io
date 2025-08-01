# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This website showcases your professional experience, skills, projects, and provides a contact form for potential clients or employers.

## Features

### 🎨 Modern Design
- Clean and professional design with smooth animations
- Responsive layout that works on all devices
- Beautiful gradient backgrounds and hover effects
- Modern typography using Inter font family

### 📱 Responsive Design
- Mobile-first approach
- Hamburger menu for mobile devices
- Optimized for tablets and desktop screens
- Touch-friendly interface

### ⚡ Interactive Elements
- Smooth scrolling navigation
- Animated skill bars
- Typing effect on hero title
- Parallax scrolling effects
- Hover animations on cards and buttons
- Form validation with notifications

### 📋 Sections Included
1. **Hero Section** - Introduction with call-to-action buttons
2. **About Section** - Personal information and statistics
3. **Experience Section** - Work history with timeline
4. **Skills Section** - Technical skills with progress bars
5. **Projects Section** - Featured projects with descriptions
6. **Contact Section** - Contact form and information

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines 45-55):
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <p class="hero-subtitle">Your Title</p>
   <p class="hero-description">Your brief description</p>
   ```

2. **About Section** (lines 75-85):
   ```html
   <p>Your personal description...</p>
   <div class="about-stats">
       <div class="stat">
           <h3>X+</h3>
           <p>Years Experience</p>
       </div>
       <!-- Add more stats as needed -->
   </div>
   ```

3. **Experience Section** (lines 105-140):
   ```html
   <div class="timeline-item">
       <div class="timeline-content">
           <h3>Your Job Title</h3>
           <h4>Company Name</h4>
           <p class="timeline-date">Year - Year</p>
           <ul>
               <li>Your responsibilities...</li>
           </ul>
       </div>
   </div>
   ```

4. **Skills Section** (lines 150-220):
   ```html
   <div class="skill-item">
       <span class="skill-name">Skill Name</span>
       <div class="skill-bar">
           <div class="skill-progress" style="width: 85%"></div>
       </div>
   </div>
   ```

5. **Projects Section** (lines 230-280):
   ```html
   <div class="project-card">
       <div class="project-image">
           <i class="fas fa-icon-name"></i>
       </div>
       <div class="project-content">
           <h3>Project Name</h3>
           <p>Project description...</p>
           <div class="project-tech">
               <span>Technology</span>
           </div>
           <div class="project-links">
               <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
               <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
           </div>
       </div>
   </div>
   ```

6. **Contact Section** (lines 290-320):
   ```html
   <div class="contact-item">
       <i class="fas fa-envelope"></i>
       <span>your.email@example.com</span>
   </div>
   <div class="contact-item">
       <i class="fas fa-phone"></i>
       <span>+1 (555) 123-4567</span>
   </div>
   <div class="contact-item">
       <i class="fas fa-map-marker-alt"></i>
       <span>Your Location</span>
   </div>
   ```

### Colors and Styling
The website uses a blue and purple color scheme. To change colors, update the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-blue: #2563eb;
--primary-purple: #7c3aed;
--accent-yellow: #fbbf24;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1f2937;
```

### Fonts
The website uses the Inter font family. To change fonts, update the Google Fonts link in `index.html` and the font-family property in `styles.css`.

### Icons
The website uses Font Awesome icons. You can find more icons at [Font Awesome](https://fontawesome.com/icons).

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for better performance
- Responsive images and icons
- Smooth animations with hardware acceleration
- Lazy loading for better page load times

## SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Deployment

To deploy your website:

1. **GitHub Pages**:
   - Push your code to a GitHub repository
   - Go to Settings > Pages
   - Select your main branch as source

2. **Netlify**:
   - Drag and drop your folder to Netlify
   - Or connect your GitHub repository

3. **Vercel**:
   - Import your GitHub repository
   - Deploy automatically

## Customization Tips

1. **Add Real Images**: Replace placeholder icons with actual photos
2. **Update Links**: Add real links to your projects and social media
3. **Form Handling**: Connect the contact form to a service like Formspree or Netlify Forms
4. **Analytics**: Add Google Analytics or other tracking tools
5. **Domain**: Purchase a custom domain for a more professional look

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing this website or have questions, feel free to reach out!

---

**Built with ❤️ using HTML, CSS, and JavaScript** 