# QuantLab AI Landing Page

A modern, responsive landing page for QuantLab AI - The AI-Powered Backtesting Lab for Traders.

## Features

- **Modern Design**: Clean, professional design with gradient backgrounds and smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Email Collection**: Built-in waitlist form with validation and success/error states
- **Social Proof**: Georgia Tech credibility badge and testimonial section
- **Performance Optimized**: Fast loading with optimized CSS and JavaScript

## Sections

1. **Navigation Bar**: Fixed header with smooth scrolling navigation
2. **Hero Section**: Logo, headline, description, and dashboard mockup
3. **Features Section**: Key benefits and features of QuantLab AI
4. **Demo Section**: Placeholder for interactive demo
5. **Waitlist Section**: Email collection form with benefits
6. **Social Proof**: Georgia Tech credibility and testimonials
7. **Footer**: Links and social media

## Files Structure

```
quantlab_landingpage/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactions and form handling
└── README.md           # This file
```

## Setup Instructions

1. **Clone or Download**: Get the files to your local machine
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **Local Server** (Optional): For development, you can use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Email Integration
To integrate with email services like Tally.so or ConvertKit:

1. **Tally.so Integration**:
   - Create a form at [tally.so](https://tally.so)
   - Replace the form action in `index.html` with your Tally form URL
   - Update the JavaScript form handling in `script.js`

2. **ConvertKit Integration**:
   - Get your form endpoint from ConvertKit
   - Update the form action and add your API key
   - Modify the JavaScript to handle ConvertKit's response format

### Analytics Integration
Add Google Analytics or other tracking:

```html
<!-- Add to <head> section -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### Color Scheme
The current color scheme uses:
- Primary: `#667eea` (Blue)
- Secondary: `#764ba2` (Purple)
- Accent: `#ffd700` (Gold)
- Success: `#4ecdc4` (Teal)
- Error: `#ff6b6b` (Red)

To change colors, update the CSS variables in `styles.css`.

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Performance

- Optimized CSS with efficient selectors
- Minimal JavaScript with event delegation
- Responsive images and lazy loading support
- Smooth animations using CSS transforms

## Deployment

### Static Hosting
Deploy to any static hosting service:
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload files to an S3 bucket

### Custom Domain
1. Update any absolute URLs in the HTML
2. Configure your domain's DNS settings
3. Add SSL certificate for HTTPS

## Contact

For questions or support regarding this landing page, please contact the development team.

---

**QuantLab AI** - The AI-Powered Backtesting Lab for Traders
Backed by Georgia Tech engineers & quant researchers
