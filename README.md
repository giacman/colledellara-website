# Colle dell'Ara - Coming Soon Website

https://www.colledellaralabro.it

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

### Contact Form Configuration

The contact form uses **[Web3Forms](https://web3forms.com)** to send emails without a backend server.

**Current Configuration:**
- Emails sent to: `lucioni.a@googlemail.com`
- Access Key: `b5f7b9e1-ca7d-4e5b-b188-3ea676cdba74`
- Free tier: 250 submissions/month
- No activation required, works immediately

**To change the email address:**
1. Go to [web3forms.com](https://web3forms.com)
2. Enter your new email address
3. Get a new Access Key
4. Update the `access_key` value in `index.html`:
   ```html
   <input type="hidden" name="access_key" value="YOUR_NEW_KEY_HERE">
   ```

**To view submissions:**
- Check your email inbox
- Or login to [Web3Forms Dashboard](https://web3forms.com/dashboard) to see all submissions

## 📦 Technologies Used

- **Tailwind CSS** (via CDN) - Utility-first CSS framework
- **Font Awesome 6** - Icon library
- **Google Fonts** - Lato font family
- **Web3Forms** - Contact form email delivery (free, no backend required)
- **Vanilla JavaScript** - For smooth scroll navigation

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

