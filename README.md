# SK Lawyers - Professional Legal Services

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-success)](https://pages.github.com/)

Professional multilingual website for SK Lawyers - Expert legal services in intellectual property, international arbitration, and corporate law across MENA and Europe.

## 🌐 Live Website

**English (Default):** [sklawyers.cc](https://sklawyers.cc)  
**French:** [sklawyers.cc/index_fr.html](https://sklawyers.cc/index_fr.html)  
**Arabic:** [sklawyers.cc/index_ar.html](https://sklawyers.cc/index_ar.html)

---

## 📋 About

SK Lawyers is a bilingual law firm founded by Professor Salma Khaled, providing expert legal counsel at the intersection of intellectual property, corporate strategy, and international dispute resolution.

### Practice Areas:
- 🏛️ **Intellectual Property** - Patents, trademarks, copyright
- ⚖️ **International Arbitration** - ICC, ICSID, UNCITRAL proceedings
- 🏢 **Corporate & Commercial Law** - M&A, governance, contracts
- 🏦 **Banking & Finance Law** - Regulatory compliance, transactions
- 💻 **E-Commerce & Digital Law** - Data protection, cybersecurity
- 🤝 **Competition Law** - Antitrust, merger control

### Offices:
- 🇫🇷 **Paris** - 205 bis, Avenue Daumesnil, 75012 Paris
- 🇹🇳 **Tunis** - Complexe les Métiers, Suite B23, Les Jardins de Carthage, 2016

---

## 🚀 Features

### Multilingual Support
- ✅ English, French, and Arabic versions
- ✅ Seamless language switching
- ✅ RTL layout for Arabic
- ✅ Proper SEO for each language

### Design
- ✅ Clean, professional aesthetic
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Accessible navigation
- ✅ Optimized performance

### Functionality
- ✅ Contact form with validation
- ✅ CAPTCHA protection (Cloudflare Turnstile)
- ✅ Real-time form validation
- ✅ Email submission to salma@sklawyers.cc

### SEO & Performance
- ✅ Structured data (Schema.org)
- ✅ Open Graph tags
- ✅ Hreflang tags for multilingual SEO
- ✅ Optimized images
- ✅ Fast loading times

---

## 📁 Repository Structure

```
SK/
├── index.html              # English version (default)
├── index_fr.html           # French version
├── index_ar.html           # Arabic version (RTL)
├── SKLightCream.png        # Logo - light background
├── Salma_1.png             # Hero section image
├── Salma_2.JPG             # About section image
├── DRIMAN.png              # Organization logo
├── OTDAV.png               # Organization logo
├── ICC_TN.JPG              # Organization logo
├── IJR.JPG                 # Organization logo
├── og-image.jpg            # Social media preview image
├── CNAME                   # Custom domain configuration
├── README.md               # This file
└── docs/
    ├── GITHUB_DEPLOYMENT_GUIDE.md
    ├── CONTACT_FORM_SETUP_GUIDE.md
    ├── FRENCH_TRANSLATION_MAPPING.md
    └── ARABIC_TRANSLATION_MAP.md
```

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Fonts:** Google Fonts (Cormorant Garamond, Inter, Almarai)
- **Forms:** FormSubmit.co / Formspree
- **CAPTCHA:** Cloudflare Turnstile
- **Hosting:** GitHub Pages
- **Domain:** sklawyers.cc

---

## 📝 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/SK.git
cd SK
```

### 2. Configure Forms

#### Arabic Form (FormSubmit.co):
- Already configured
- First submission requires email confirmation
- Check `salma@sklawyers.cc` and confirm

#### English & French Forms (Formspree):
1. Sign up at [formspree.io](https://formspree.io)
2. Create form with email: `salma@sklawyers.cc`
3. Replace `YOUR_FORM_ID` in `index.html` and `index_fr.html`

### 3. Configure CAPTCHA

1. Get Turnstile site key from [Cloudflare](https://dash.cloudflare.com)
2. Replace `YOUR_TURNSTILE_SITE_KEY` in all HTML files

### 4. Deploy to GitHub Pages

1. Push all files to GitHub
2. Go to Settings → Pages
3. Enable Pages (Source: main branch, folder: root)
4. Site will be live at: `https://YOUR_USERNAME.github.io/SK/`

See detailed instructions in `docs/GITHUB_DEPLOYMENT_GUIDE.md`

---

## 🔧 Local Development

### Requirements:
- Modern web browser
- Local web server (optional, for testing)

### Running Locally:

**Option 1: Python Simple Server**
```bash
python -m http.server 8000
# Visit: http://localhost:8000
```

**Option 2: VS Code Live Server**
1. Install "Live Server" extension
2. Right-click `index.html` → "Open with Live Server"

**Option 3: Direct File**
- Simply open `index.html` in your browser
- Some features may require a server

---

## 📧 Contact Form Configuration

### Form Fields:
- Full name (required)
- Organisation (optional)
- Email address (required)
- Email confirmation (required)
- Subject (required)
- Message (required)
- Turnstile verification (required)

### Form Validation:
- ✅ Real-time email format checking
- ✅ Email confirmation matching
- ✅ Required field validation
- ✅ CAPTCHA verification
- ✅ Character limits

### Submission Flow:
1. User fills form → validation
2. Turnstile verification
3. Submit → Form data sent to salma@sklawyers.cc
4. Success message displays
5. Form clears automatically

---

## 🌍 Multilingual Implementation

### Language Structure:
- **English:** `index.html` (default/root)
- **French:** `index_fr.html`
- **Arabic:** `index_ar.html`

### SEO Configuration:
- Each version has proper `lang` and `dir` attributes
- Hreflang tags link all versions
- Language-specific meta tags and Open Graph
- Canonical URLs properly set

### Language Toggle:
- Top-right navigation on all pages
- Active language highlighted
- Preserves scroll position
- Mobile responsive

---

## 📊 Analytics & Monitoring

To add analytics:

1. **Google Analytics:**
   - Add tracking code before `</head>`
   - Track page views, form submissions, language switching

2. **Google Search Console:**
   - Verify domain ownership
   - Submit sitemap
   - Monitor search performance

3. **Form Monitoring:**
   - Check Formspree/FormSubmit dashboards
   - Monitor submission rates
   - Review spam filtering

---

## 🔐 Security

- ✅ HTTPS enforced via GitHub Pages
- ✅ No sensitive data in repository
- ✅ CAPTCHA prevents spam submissions
- ✅ Form validation (client + server side)
- ✅ CSP headers can be added via Cloudflare

---

## 🐛 Troubleshooting

### Forms not working?
- Check browser console (F12)
- Verify Form ID / Site Key configuration
- Confirm email confirmation (FormSubmit.co)

### Images not loading?
- Verify file names match exactly (case-sensitive)
- Check all images are in root directory
- Clear browser cache

### Language toggle not working?
- Verify all three HTML files exist
- Check file names: `index.html`, `index_fr.html`, `index_ar.html`

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Salma Khaled**  
Professor of Private Law | Attorney (Paris & Tunis Bars)

- Website: [sklawyers.cc](https://sklawyers.cc)
- Email: salma@sklawyers.cc
- LinkedIn: [linkedin.com/in/salma-khaled](https://linkedin.com/in/salma-khaled-4b11b119/)

---

## 📮 Contact

For website issues or updates:
- Open an issue in this repository
- Email: salma@sklawyers.cc

For legal inquiries:
- Use contact form on website
- Email: salma@sklawyers.cc
- Paris Office: +33 (0) [PHONE]
- Tunis Office: +216 98 32 85 27

---

## 🙏 Acknowledgments

- Design inspired by modern legal practice aesthetics
- Fonts: Cormorant Garamond, Inter, Almarai
- Icons: Custom SVG designs
- Form handling: Formspree & FormSubmit.co
- CAPTCHA: Cloudflare Turnstile
- Hosting: GitHub Pages

---

**© 2025 SK Lawyers. All rights reserved.**
