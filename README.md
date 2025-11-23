# 🚖 Zaid Lahbari - Professional Taxi & Transport Services Website

![Taxi Services](https://img.shields.io/badge/Service-Taxi%20%26%20Transport-yellow)
![Location](https://img.shields.io/badge/Location-Marrakech%2C%20Morocco-red)
![Languages](https://img.shields.io/badge/Languages-FR%20%7C%20EN%20%7C%20AR-blue)
![Status](https://img.shields.io/badge/Status-Ready%20to%20Deploy-green)

A modern, professional static website for Zaid Lahbari's taxi and transportation services in Marrakech, Morocco. Features a fully responsive design, multi-language support (French, English, Arabic), and seamless WhatsApp integration.

## ✨ Features

### 🌍 Multi-Language Support
- **French** (Default)
- **English**
- **Arabic** (with RTL support)
- Automatic language detection based on browser settings
- Persistent language preference using localStorage

### 📱 Responsive Design
- Mobile-first approach
- Optimized for all screen sizes (mobile, tablet, desktop)
- Touch-friendly navigation
- Fast loading times

### 🎨 Modern UI/UX
- Clean, professional design inspired by business card colors (yellow & black)
- Smooth scroll animations (AOS library)
- Interactive destination slider with auto-play
- Floating WhatsApp button for instant contact
- Scroll-to-top functionality

### 💬 Contact Features
- **Direct WhatsApp Integration** - One-click messaging
- **Phone Call Links** - Instant dialing
- **Contact Form** - Sends formatted message to WhatsApp
- **Email Link** - Alternative contact method

### 🎯 Key Sections
1. **Hero Section** - Eye-catching introduction with CTA buttons
2. **Services** - Taxi, Airport Transfers, Mini-Bus, Guided Tours
3. **Marrakech Attractions** - Local tourist sites
4. **Destinations Slider** - Interactive showcase of excursions
5. **Activities** - Quad, Camel rides, Hammam, Hot Air Balloon, etc.
6. **Testimonials** - Social proof from satisfied clients
7. **Contact** - Multiple ways to get in touch
8. **Footer** - Complete information and quick links

### ⚡ Performance Features
- Lazy loading images
- Optimized animations
- Minimal external dependencies
- SEO-friendly structure

## 📁 Project Structure

```
Zaid/
├── index.html              # Main HTML file
├── styles.css              # All styles and responsive design
├── script.js               # JavaScript functionality
├── README.md               # This file
├── DEPLOYMENT.md           # Deployment guide
└── assets/
    └── images/
        ├── hero/           # Hero background images
        ├── destinations/   # Destination photos
        ├── attractions/    # Marrakech sites photos
        └── README.md       # Image guide
```

## 🚀 Quick Start

### Option 1: Open Locally
1. Download all files to your computer
2. Double-click `index.html` to open in browser
3. That's it! The website runs entirely in the browser

### Option 2: Use Live Server (Recommended for Development)
1. Install [VS Code](https://code.visualstudio.com/)
2. Install "Live Server" extension
3. Right-click `index.html` → "Open with Live Server"
4. Website opens at `http://localhost:5500`

## 🖼️ Customizing Images

The website currently uses placeholder images from Unsplash. To add your own:

1. Place your images in the `assets/images/` folder
2. Follow naming conventions in `assets/images/README.md`
3. Update image paths in `index.html`

**Recommended image sizes:**
- Hero images: 1920x1080px
- Destination images: 1200x800px
- Attraction images: 800x600px

See `assets/images/README.md` for detailed instructions.

## 📝 Customization Guide

### Change Contact Information
Edit in `index.html`:

```html
<!-- Phone number -->
<a href="tel:+212699740404">+212 6 99 74 04 04</a>

<!-- WhatsApp -->
<a href="https://wa.me/212699740404">

<!-- Email -->
<a href="mailto:Zaidsayfdln2@gmail.com">Zaidsayfdln2@gmail.com</a>
```

### Change Colors
Edit in `styles.css`:

```css
:root {
    --primary-yellow: #FFC107;  /* Main yellow color */
    --dark-gray: #2C2C2C;       /* Dark backgrounds */
    --black: #1a1a1a;           /* Text and accents */
}
```

### Add/Remove Destinations
Edit the slider in `index.html` and update `script.js` translations.

### Modify Text Content
All text is managed through the `translations` object in `script.js`.

## 🌐 Deployment Options

### Free Static Hosting Services

#### 1. **Netlify** ⭐ (Recommended)
- Easiest deployment
- Free SSL certificate
- Custom domain support
- Automatic deployments from Git

**Steps:**
1. Create account at [netlify.com](https://netlify.com)
2. Drag & drop your project folder
3. Done! Get instant URL like `zaid-taxi.netlify.app`

#### 2. **Vercel**
- Similar to Netlify
- Fast global CDN
- Free custom domain

**Steps:**
1. Sign up at [vercel.com](https://vercel.com)
2. Import project
3. Deploy with one click

#### 3. **GitHub Pages**
- Free hosting via GitHub
- Good for version control
- Custom domain support

**Steps:**
1. Create GitHub account
2. Create repository named `username.github.io`
3. Upload files
4. Enable Pages in settings
5. Access at `username.github.io`

#### 4. **Cloudflare Pages**
- Fast CDN
- Free SSL
- Unlimited bandwidth

#### 5. **Firebase Hosting**
- Google's hosting platform
- Fast and reliable
- Free tier available

### Custom Domain Setup

After deploying, you can use a custom domain like:
- `www.zaidtaxi.com`
- `marrakech-taxi.ma`
- `zaidlahbari.com`

**Steps:**
1. Purchase domain from:
   - [Namecheap](https://namecheap.com)
   - [Google Domains](https://domains.google)
   - [OVH](https://ovh.com) (popular in Morocco)

2. Point domain to your hosting:
   - Follow hosting provider's DNS instructions
   - Usually takes 24-48 hours to propagate

See `DEPLOYMENT.md` for detailed deployment instructions.

## 📱 Testing Checklist

Before going live, test:

- [ ] All links work (phone, email, WhatsApp)
- [ ] Contact form sends to WhatsApp correctly
- [ ] Language switcher works (FR/EN/AR)
- [ ] Mobile menu opens and closes
- [ ] Destination slider navigates correctly
- [ ] Images load properly
- [ ] Website looks good on mobile phone
- [ ] Website looks good on tablet
- [ ] Website looks good on desktop
- [ ] Scroll animations work smoothly
- [ ] All sections are visible
- [ ] No console errors in browser DevTools

## 🔧 Browser Compatibility

Tested and working on:
- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Mobile Safari (iOS 14+)
- ✅ Chrome Mobile (Android 8+)

## 📦 Dependencies

### CDN Libraries (Loaded from Internet):
- **Google Fonts** - Poppins & Noto Sans Arabic
- **Font Awesome 6.4.0** - Icons
- **AOS 2.3.1** - Scroll animations

No build process or npm required! Everything runs in the browser.

## 🎨 Design Credits

- **Color Scheme:** Inspired by Zaid Lahbari's business card
- **Typography:** Poppins (Latin), Noto Sans Arabic (Arabic)
- **Icons:** Font Awesome
- **Placeholder Images:** Unsplash

## 📞 Contact Information

**Zaid Lahbari**
- 📱 Phone: +212 6 99 74 04 04
- 💬 WhatsApp: [Chat Now](https://wa.me/212699740404)
- 📧 Email: Zaidsayfdln2@gmail.com
- 📍 Location: Marrakech, Morocco
- ⏰ Available: 24/7

## 🤝 Support

### Need Help?
1. Check `DEPLOYMENT.md` for deployment issues
2. Check `assets/images/README.md` for image help
3. Contact a web developer for custom modifications

### Common Issues

**Q: Images not loading?**
- Check file paths are correct
- Ensure images are in `assets/images/` folder
- Check file extensions (.jpg, .png)

**Q: WhatsApp link not working?**
- Verify phone number format: `212699740404` (no + or spaces)
- Test on mobile device with WhatsApp installed

**Q: Website looks broken on mobile?**
- Clear browser cache
- Test in incognito/private mode
- Check browser console for errors

**Q: Language switcher not working?**
- Clear browser localStorage
- Check JavaScript is enabled
- Test in different browser

## 📄 License

This website is created for Zaid Lahbari's business use. All rights reserved.

## 🎉 What's Next?

### Future Enhancements:
- [ ] Add real customer photos (with permission)
- [ ] Create gallery section with trip photos
- [ ] Add Google Maps integration
- [ ] Implement online booking system
- [ ] Add customer review integration (Google Reviews)
- [ ] Create blog section for travel tips
- [ ] Add pricing page
- [ ] Implement dark mode toggle
- [ ] Add more destination pages

---

## 🚀 Ready to Go Live?

1. ✅ Customize contact information
2. ✅ Replace placeholder images with your photos
3. ✅ Test on mobile and desktop
4. ✅ Deploy to hosting service
5. ✅ Share your website URL with customers!

**Deployment Checklist:** See `DEPLOYMENT.md` for step-by-step guide.

---

**Made with ❤️ in Marrakech**

*Last Updated: November 2025*