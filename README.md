# Colle dell'Ara - Coming Soon Website

A beautiful coming soon landing page for Colle dell'Ara Bed & Breakfast, built with Tailwind CSS inspired by Creative Tim's Tailwind Starter Kit.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and elegant design using Tailwind CSS
- **Email Subscription**: Newsletter signup form for early access notifications
- **Smooth Animations**: Floating animations and hover effects
- **Contact Information**: Easy-to-find contact details and social media links
- **English Language**: Content in English for international audience

## 🎨 Design Highlights

- Hero section with animated logo
- Feature cards highlighting B&B amenities
- Gradient backgrounds and modern styling
- Font Awesome icons
- Google Fonts (Playfair Display & Poppins)

## 🚀 Getting Started

This is a simple static website that doesn't require any build process or dependencies.

### Quick Start

1. Simply open `index.html` in your web browser
2. Or use a simple HTTP server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` in your browser

## 📝 Customization

### Update Contact Information

Edit the contact section in `index.html`:

```html
<a href="mailto:info@colledellara.it">info@colledellara.it</a>
<a href="tel:+39123456789">+39 123 456 789</a>
```

### Update Social Media Links

Replace the `#` in social media links with actual URLs:

```html
<a href="https://facebook.com/yourpage">...</a>
<a href="https://instagram.com/yourpage">...</a>
<a href="https://wa.me/39123456789">...</a>
```

### Add Email Form Integration

To connect the email form to your backend or email service (like Mailchimp, SendGrid, etc.), update the JavaScript in the form submission handler.

## 📦 Technologies Used

- **Tailwind CSS** (via CDN) - Utility-first CSS framework
- **Font Awesome 6** - Icon library
- **Google Fonts** - Playfair Display & Poppins fonts
- **Vanilla JavaScript** - For form handling

## 🌐 Deployment

### Deploy to Vercel

**Method 1: Using npx (no installation required)**

```bash
# Deploy to Vercel without installing anything globally
npx vercel

# For production deployment
npx vercel --prod
```

**Method 2: Via Vercel Dashboard (Easiest)**

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "New Project"
4. Import your `colledellara-website` repository
5. Click "Deploy" (it auto-detects static sites)
6. Your site will be live in seconds! 🚀

### Custom Domain

After deployment, you can add a custom domain (e.g., `colledellara.com`) through the Vercel dashboard.

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Credits

- Design inspired by [Tailwind Starter Kit](https://www.creative-tim.com/learning-lab/tailwind-starter-kit) by Creative Tim
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)

---

Made with ❤️ for Colle dell'Ara B&B

