# ☕ Brew Haven Coffee Website

A modern, responsive website for a premium coffee shop. Built with HTML, CSS, and JavaScript.

## 🎨 Features

✨ **Responsive Design**
- Mobile-first approach
- Works seamlessly on all devices
- Hamburger menu for mobile navigation

☕ **Menu Showcase**
- 9 specialty coffee drinks
- Fresh pastries section
- Pricing information
- Interactive menu cards

📍 **Location & Hours**
- Store address
- Phone number
- Email contact
- Business hours
- Professional contact form

🎯 **Interactive Elements**
- Smooth scrolling navigation
- Form validation
- Menu item notifications
- Animated sections
- Mobile-responsive hamburger menu

🎨 **Professional Styling**
- Coffee-themed color scheme
- Smooth animations
- Modern UI/UX
- Hover effects

## 🚀 Quick Start

### Option 1: View Locally
1. Download all three files (index.html, styles.css, script.js)
2. Open `index.html` in your web browser
3. Done! The website works offline

### Option 2: Deploy to GitHub Pages
1. Push these files to a GitHub repository
2. Go to repository Settings
3. Scroll to "GitHub Pages" section
4. Select "main" branch as source
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 3: Deploy to Netlify (Recommended)
1. Push files to GitHub repository
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Connect your GitHub repository
5. Click "Deploy site"
6. Get a free domain and automatic deploys

### Option 4: Deploy to Vercel
1. Push files to GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Import your project
4. One-click deploy
5. Free domain included

## 📝 Customization Guide

### Change Business Information
Open `index.html` and find these sections:

```html
<!-- Address -->
123 Coffee Lane<br>Seattle, WA 98101

<!-- Phone -->
(555) 123-4567

<!-- Email -->
hello@brewhaven.com

<!-- Hours -->
Mon-Fri: 6:00 AM - 8:00 PM<br>Sat-Sun: 7:00 AM - 9:00 PM
```

Replace with your actual business details.

### Update Colors
In `styles.css`, modify the `:root` section:

```css
:root {
    --primary-color: #8B4513;        /* Main brown */
    --secondary-color: #D2691E;      /* Secondary brown */
    --accent-color: #F4A460;         /* Sandy/orange */
    --dark-color: #3E2723;           /* Dark brown */
    --light-color: #FFF8F0;          /* Cream/beige */
}
```

### Add Your Own Logo
In `index.html`, replace the coffee icon with your logo:

```html
<!-- From: -->
<i class="fas fa-coffee"></i>

<!-- To: -->
<img src="your-logo.png" alt="Brew Haven Logo" style="height: 40px;">
```

### Update Menu Items
Find the menu section and modify items, prices, and descriptions:

```html
<div class="menu-card">
    <div class="menu-icon">
        <i class="fas fa-mug-hot"></i>
    </div>
    <h3>Your Drink Name</h3>
    <p>Your description here</p>
    <span class="price">$X.XX</span>
</div>
```

### Add Images
Replace placeholder images:
```html
<!-- Find: -->
<img src="https://via.placeholder.com/400x300?text=Coffee+Shop" alt="Brew Haven Coffee Shop">

<!-- Replace with your image: -->
<img src="your-image.jpg" alt="Brew Haven Coffee Shop">
```

## 🎯 SEO Tips

1. **Meta Tags** - Already included with:
   - Title: "Brew Haven Coffee - Premium Coffee Experience"
   - Viewport: Mobile responsive
   
2. **Improve Search Rankings**:
   - Add Google Analytics (optional)
   - Submit to Google Search Console
   - Add keywords in content naturally
   - Ensure fast loading times
   - Add alt text to images

3. **For Netlify/Vercel**:
   - Enable automatic cache busting
   - Use GZIP compression
   - CDN speeds up global access

## 📞 Contact Form Integration

Currently, the form logs to browser console. To actually send emails, integrate with:

### Option A: Formspree (Free)
1. Go to [formspree.io](https://formspree.io)
2. Create account and add your email
3. Replace `<form class="contact-form">` with:

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_ID" method="POST">
```

### Option B: EmailJS (Free)
1. Go to [emailjs.com](https://emailjs.com)
2. Follow setup instructions
3. Add their library to your HTML

### Option C: Backend Service
Deploy a simple backend (Node.js, Python, etc.) to handle emails.

## 🌐 Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- IE11: ⚠️ Partial support (animations may vary)

## 📱 Mobile Responsiveness

- Hamburger menu for mobile
- Touch-friendly buttons
- Optimized for screens as small as 320px
- Tested on:
  - iPhone (5s and newer)
  - Android phones
  - Tablets
  - Desktop screens

## 🔧 Technical Details

**Files Included:**
- `index.html` - Structure (9.2 KB)
- `styles.css` - Styling (10.8 KB)
- `script.js` - Functionality (3.5 KB)

**Dependencies:**
- Font Awesome Icons (CDN) - For icons
- No frameworks required!
- Pure vanilla JavaScript

**Performance:**
- Lightweight & fast-loading
- Optimized CSS
- Minimal JavaScript
- Google PageSpeed friendly

## 📊 Features by Section

### Navigation
- Sticky header
- Responsive menu
- Smooth scrolling links

### Hero
- Full-width banner
- Gradient background
- Call-to-action button

### About
- Two-column layout
- Feature list with icons
- Image showcase

### Menu
- 9 coffee items
- Responsive grid
- Hover animations
- Price display

### Contact
- 4 info cards
- Contact form
- Email validation
- Success notifications

### Footer
- Quick links
- Social media
- Copyright info

## 🎓 Learning Resources

Want to customize further? Check out:
- [MDN Web Docs](https://developer.mozilla.org)
- [CSS Tricks](https://css-tricks.com)
- [JavaScript.info](https://javascript.info)

## 📄 License

Free to use and modify for your business!

## 🤝 Support

For issues or questions:
1. Check browser console (F12 → Console tab)
2. Review the code comments
3. Test in different browsers
4. Verify all files are in same folder

---

**Made with ☕ for coffee lovers everywhere!**

Version 1.0 | May 2024 | Brew Haven Coffee