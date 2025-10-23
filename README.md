# Harshith's Portfolio Website

A modern, responsive portfolio website showcasing my experience as a Machine Learning Engineer and Software Developer.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Mobile-First**: Optimized for mobile devices with hamburger navigation
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **SEO Friendly**: Semantic HTML structure for better search engine visibility

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 🎨 Design Features

### Color Scheme
- Primary Blue: `#2563eb`
- Accent Yellow: `#fbbf24`
- Gradient Backgrounds: Purple to blue gradients
- Clean whites and grays for content

### Typography
- Font Family: Inter (Google Fonts)
- Responsive font sizes
- Clear hierarchy with proper contrast

### Animations
- Smooth scroll behavior
- Fade-in animations on scroll
- Hover effects on interactive elements
- Parallax scrolling effects
- Counter animations for statistics

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (optional, for development)

### Installation

1. **Clone or Download** the portfolio files to your local machine

2. **Open the Portfolio**
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python (if installed)
     python -m http.server 8000
     
     # Using Node.js (if installed)
     npx serve .
     ```

3. **Customize the Content**
   - Edit `index.html` to update your personal information
   - Modify `styles.css` to change colors, fonts, or layout
   - Update `script.js` to add new interactive features

## ✏️ Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines ~45-65):
   - Change name, title, and description
   - Update social media links

2. **About Section** (lines ~80-110):
   - Modify the about text
   - Update statistics (years of experience, projects, etc.)

3. **Skills Section** (lines ~115-150):
   - Add or remove skill categories
   - Update skill tags with your technologies

4. **Experience Section** (lines ~155-200):
   - Update work experience details
   - Add or remove timeline items

5. **Projects Section** (lines ~205-280):
   - Replace with your actual projects
   - Update project descriptions and technologies
   - Add real project links

6. **Contact Section** (lines ~285-320):
   - Update contact information
   - Modify contact form if needed

### Styling Customization

#### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --accent-color: #fbbf24;
    --text-color: #333;
    --bg-color: #fff;
}
```

#### Fonts
Change the font family in the CSS:
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

#### Layout
- Modify grid layouts in the CSS
- Adjust spacing and padding
- Change section heights and margins

### Adding New Sections

1. **HTML Structure**:
   ```html
   <section id="new-section" class="new-section">
       <div class="container">
           <h2 class="section-title">Section Title</h2>
           <!-- Your content here -->
       </div>
   </section>
   ```

2. **CSS Styling**:
   ```css
   .new-section {
       padding: 80px 0;
       background: #f8fafc;
   }
   ```

3. **Navigation**:
   Add the new section to the navigation menu in `index.html`

## 🔧 Advanced Customization

### Adding Animations
The portfolio includes several animation features:
- Scroll-triggered animations
- Hover effects
- Counter animations
- Parallax scrolling

### Form Functionality
The contact form is currently set up for demonstration. To make it functional:
1. Add a backend service (Node.js, Python Flask, etc.)
2. Update the form submission handler in `script.js`
3. Add proper validation and error handling

### Performance Optimization
- Minify CSS and JavaScript for production
- Optimize images (use WebP format when possible)
- Enable gzip compression on your server
- Use a CDN for external resources

## 📊 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

This is a personal portfolio template. Feel free to:
- Fork and customize for your own use
- Submit issues or suggestions
- Create pull requests for improvements

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**V L Sivasai Mani Harshith Bhattaram**
- Email: bhattaramvlsivasaimaniharshith@gmail.com
- Phone: (716) 232-0462
- LinkedIn: [linkedin.com/in/harshith68](https://www.linkedin.com/in/harshith68)
- GitHub: [github.com/maniharshith68](https://github.com/maniharshith68)

---

**Note**: This portfolio is based on my resume and professional experience. Feel free to customize it according to your own background and preferences.
