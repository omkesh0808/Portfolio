<div align="center">

# 💼 Omkesh's Portfolio Website

</div>

A modern, responsive personal portfolio website showcasing my work as a full-stack web developer. Built with React+Golang and integrated with a stunning animated particle background.

---

## 🚀 Features

### ✨ **Core Features**
- Responsive design for all screen sizes  
- Interactive hamburger menu for mobile view  
- Hero section with animated name using GSAP  
- Snowfall particle background using [particles.js](http://vincentgarreau.com/particles.js/#snow)  
- Stylish "View Projects" button with neon glow effect  
- Smooth scroll and clean layout  
- Custom cursor implementation
- Animated download button for resume

### 📧 **Contact Form**
- Functional contact form with Formspree integration
- Form validation and user feedback
- Loading states and success/error messages
- Professional styling with hover effects
- Contact information display with icons

### ⚡ **Performance Optimizations**
- Lazy loading for images
- Reduced motion support for accessibility
- Optimized animations with `will-change` and `contain`
- Service Worker for offline functionality
- PWA (Progressive Web App) support
- Critical CSS optimization
- Font loading optimization

### 🐙 **GitHub Integration**
- Live GitHub statistics (repos, stars, followers, commits)
- Recent activity feed with event types
- Most used programming languages display
- Real-time data from GitHub API
- Fallback data for offline viewing

### 🎨 **Enhanced UI/UX**
- Dark theme with custom color scheme
- Smooth animations and transitions
- Interactive elements with hover effects
- Accessibility improvements
- Print-friendly styles

---

## 🛠️ Tech Stack

- **Golang** – Expert in backend development
- **ReactJS** – Creates web pages using react framework
- **HTML5** – Semantic markup with accessibility features
- **CSS3** – Custom styling + Bootstrap 5 + Tailwind CSS
- **JavaScript** – Core interactivity, animations, and API integrations
- **GSAP** – Advanced animations and scroll triggers
- **GitHub API** – Live coding activity integration
- **Service Worker** – Offline functionality and caching

---

## 📱 PWA Features

- **Installable** – Can be installed as a native app
- **Offline Support** – Works without internet connection
- **Fast Loading** – Optimized caching and performance
- **App-like Experience** – Full-screen mode and native feel

---

## 📸 Live Preview

👉 [Live Demo](https://omkesh0808.github.io/Portfolio/)

## 📸 Screenshot

<TODO- Comming soon>

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/omkesh0808/Portfolio.git
   cd Portfolio
   ```

2. **Open in browser**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Or simply open index.html in your browser
   ```

3. **Customize**
   - Update personal information in `index.html`
   - Modify colors in `styles.css`
   - Add your own projects and content
   - Update GitHub username in `script.js`

---

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom styles and animations
├── script.js           # JavaScript functionality
├── manifest.json       # PWA manifest
├── sw.js              # Service Worker
├── assets/            # Images and media files
└── README.md          # Project documentation
```

---

## 🔧 Configuration

### Contact Form
Update the Formspree endpoint in `script.js`:
```javascript
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

### GitHub Integration
Update your GitHub username in `script.js`:
```javascript
const username = 'YOUR_GITHUB_USERNAME';
```

---

## 📈 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📞 Contact

- **Email**: omkesh0808@gmail.com
- **LinkedIn**: [Omkesh Sajjanwar](https://www.linkedin.com/in/omkesh-sajjanwar-114860159)
- **GitHub**: [@omkesh0808](https://github.com/omkesh0808)
- **Instagram**: [@Comming soon]()
