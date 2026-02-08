# Triton Restaurant Website

A sophisticated, elegant restaurant website built with modern web technologies, featuring Mediterranean-inspired design aesthetics.

## 🎨 Design Features

- **Elegant Typography**: Cormorant Garamond for headings paired with Montserrat for body text
- **Refined Color Palette**: Navy blues, cream, and gold accents inspired by Mediterranean aesthetics
- **Smooth Animations**: Subtle fade-ins, hover effects, and scroll-triggered animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Modern Layout**: Clean, spacious design with attention to visual hierarchy

## 📁 File Structure

```
triton-restaurant/
├── index.html          # Main homepage
├── menu.html           # Full menu page with categories
├── styles.css          # Complete stylesheet
├── script.js           # Interactive functionality
├── assets/
│   ├── images/         # All images (logo, food photos, restaurant interior)
│   └── menu/           # Menu page images
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Open Locally
1. Download all files maintaining the folder structure
2. Open `index.html` in your web browser
3. Navigate through the site using the menu

### Option 2: Deploy to Web Server
1. Upload all files to your web hosting service
2. Maintain the exact folder structure
3. Ensure all image paths remain relative
4. Configure your domain to point to `index.html`

## 📄 Pages Included

### Homepage (index.html)
- **Hero Section**: Full-screen image with elegant typography
- **About Section**: Restaurant story and key features
- **Featured Dishes**: Showcasing signature items with images
- **Gallery**: Visual showcase of food and ambiance
- **Contact**: Location, hours, phone, email, and embedded map

### Menu Page (menu.html)
- **Complete Menu**: All categories organized and filterable
- **Category Navigation**: Sticky navigation for easy browsing
- **Beverages**: Coffee, tea, shakes, smoothies, and house specials
- **Food Categories**: Soups, salads, appetizers, pizza, pasta, Indian cuisine, Asian dishes, desserts
- **Interactive Filtering**: Click categories to show/hide menu sections

## 🎯 Features

### Navigation
- Sticky navigation bar with scroll effect
- Smooth scrolling to sections
- Mobile-responsive hamburger menu
- Active page highlighting

### Interactive Elements
- Menu category filtering
- Image lightbox for gallery
- Scroll-triggered animations
- Hover effects on cards and buttons

### Performance
- Lazy loading for images
- Debounced scroll events
- Optimized animations
- Clean, semantic HTML

## 🎨 Color Palette

- **Primary Navy**: #2B4162 - Main brand color
- **Primary Blue**: #3A5A7E - Secondary brand color
- **Accent Gold**: #D4AF37 - Call-to-action and highlights
- **Accent Rose**: #C9A8A8 - Subtle accent
- **Neutral Cream**: #F5F1E8 - Background
- **Neutral Beige**: #E8DFD0 - Alternate background
- **Text Primary**: #2C2C2C - Main text
- **Text Secondary**: #6B6B6B - Secondary text

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## 🔧 Customization Guide

### Update Restaurant Info
Edit the contact details in both `index.html` and `menu.html`:
- Address (line ~420 in index.html)
- Phone number
- Email address
- Operating hours
- Google Maps embed (replace iframe src)

### Add/Remove Menu Items
In `menu.html`, find the appropriate category section and:
1. Copy an existing `<div class="menu-item">` block
2. Update the dish name, price, and description
3. Maintain the HTML structure for consistent styling

### Change Colors
In `styles.css`, update the CSS variables in the `:root` section (lines 10-20):
```css
--primary-navy: #YourColor;
--accent-gold: #YourColor;
/* etc. */
```

### Add Social Media Links
Update the footer sections in both HTML files:
- Replace `#` with actual social media URLs
- Customize the link text/icons as needed

## 🌐 Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information (Current Placeholder)

**Address**: 123 Mediterranean Lane, Coastal District, CD 45678  
**Phone**: +1 (555) 123-4567  
**Email**: hello@tritonrestaurant.com  
**Hours**: 
- Monday - Thursday: 11:00 AM - 10:00 PM
- Friday - Saturday: 11:00 AM - 11:00 PM
- Sunday: 10:00 AM - 9:00 PM

*Note: Update these with your actual restaurant information*

## 🎓 Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern layouts with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Cormorant Garamond & Montserrat
- **No frameworks required**: Pure vanilla code for maximum performance

## ⚡ Performance Tips

1. **Image Optimization**: Compress images before upload for faster loading
2. **CDN**: Consider using a CDN for Google Fonts
3. **Caching**: Enable browser caching on your server
4. **Minification**: Minify CSS and JS for production

## 🎨 Design Credits

- Color palette inspired by Mediterranean aesthetics
- Typography choices for elegance and readability
- Layout designed for optimal user experience
- Photography styling that complements the cuisine

## 📝 License

This website template is provided as-is for the Triton Restaurant project.

## 🤝 Support

For questions or customization assistance, consult with your web developer.

---

**Built with care for Triton Restaurant** 🍽️  
*Where Mediterranean heritage meets global flavors*
