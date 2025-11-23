👌Contact for web Projects or Application Projects
# 🚀 Sanjeevi G - Portfolio Website

A modern, responsive portfolio website showcasing my skills as a Full Stack Developer specializing in mobile and web development.

## 🌟 Features

- **Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- **Dark/Light Theme** - Toggle between themes with smooth transitions
- **Interactive Animations** - Canvas-based tech stack visualization and smooth scrolling effects
- **Email Contact Form** - Integrated with EmailJS for direct contact functionality
- **Dynamic Content** - Auto-typing effect and infinite scrolling marquees
- **Modern UI/UX** - Clean design with glassmorphism effects and smooth animations
- **Performance Optimized** - Fast loading with preloader and optimized assets

## 🛠️ Tech Stack

### Frontend

- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced styling with custom properties and animations
- **JavaScript (ES6+)** - Modern vanilla JavaScript for interactions
- **Font Awesome** - Icon library for UI elements
- **Google Fonts** - Poppins and Fira Code typography

### Services

- **EmailJS** - Email service integration for contact form
- **GitHub Pages** - Hosting and deployment

## 🎨 Design Features

- **Glassmorphism UI** - Modern frosted glass effects
- **Parallax Scrolling** - Smooth scrolling animations
- **Interactive Canvas** - Rotating tech stack visualization
- **Continuous Marquee** - Auto-scrolling project and skills sections
- **Spotlight Cards** - Mouse-following highlight effects
- **Responsive Navigation** - Mobile-friendly hamburger menu

## 📱 Sections

1. **Hero Section** - Introduction with dynamic typing effect
2. **About** - Personal introduction and background
3. **Skills** - Interactive tech stack with animations
4. **Projects** - Showcase of development work
5. **Credentials** - Education and certifications
6. **Contact** - Email form and social links

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Sanjeevi18/Portfolio.git
   cd Portfolio
   ```

2. **Setup EmailJS (Optional)**

   - Create an account at [EmailJS](https://www.emailjs.com/)
   - Update the configuration in `keys.js`:
     ```javascript
     const EMAILJS_CONFIG = {
       publicKey: "your_public_key",
       serviceId: "your_service_id",
       templateId: "your_template_id",
     };
     ```

3. **Run locally**

   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server

     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (with live-server)
     npx live-server
     ```

4. **Access the website**
   - Direct: `file:///path/to/index.html`
   - Local server: `http://localhost:8000`

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css          # Stylesheet with all animations and responsive design
├── script.js          # JavaScript functionality and interactions
├── keys.js            # EmailJS configuration
├── assets/            # Static assets
│   ├── MYPIC.jpg      # Profile picture
│   └── sanjeevi_resume.pdf  # Resume file
└── README.md          # This file
```

## 🎯 Key Features Breakdown

### Interactive Canvas Animation

- Rotating tech stack icons around a circular path
- Hover effects that expand the circle and increase rotation speed
- Responsive design that adapts to screen size

### Smooth Scrolling System

- Custom implementation for project cards and skill marquees
- Auto-scrolling with pause on user interaction
- Touch-friendly for mobile devices

### Theme Switcher

- Persistent theme storage in localStorage
- Smooth transitions between light and dark modes
- Dynamic icon updates

### Contact Form

- Integrated with EmailJS for serverless email functionality
- Form validation and user feedback
- Success/error state handling

## 📱 Mobile Optimization

- Touch-friendly navigation and interactions
- Optimized marquee scrolling for mobile devices
- Responsive breakpoints for all screen sizes
- Mobile-first approach in CSS

## 🎨 Customization

### Colors

Update CSS custom properties in `style.css`:

```css
:root {
  --primary: #00f2ea;
  --secondary: #ff6b35;
  --accent: #4facfe;
  /* ... other variables */
}
```

### Content

- Update personal information in `index.html`
- Modify skills array in `script.js`
- Replace profile picture in `assets/MYPIC.jpg`

### EmailJS Setup

1. Create EmailJS account
2. Setup email service and template
3. Update `keys.js` with your credentials

## 🌐 Deployment

### GitHub Pages

1. Push code to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (main)
4. Access at: `https://yourusername.github.io/repository-name`

### Other Platforms

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect GitHub repository
- **Firebase Hosting**: Use Firebase CLI

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- Lighthouse Score: 95+ (Performance, Accessibility, Best Practices, SEO)
- Optimized images and assets
- Minimal external dependencies
- Efficient animation implementations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Sanjeevi G**

- Portfolio: [Live Demo](https://sanjeevi18.github.io/Portfolio)
- GitHub: [@Sanjeevi18](https://github.com/Sanjeevi18)
- Email: [Contact through portfolio](https://sanjeevi18.github.io/Portfolio#contact)

---

⭐ **If you found this portfolio helpful, please give it a star!**

---

_Built with ❤️ by Sanjeevi G_
