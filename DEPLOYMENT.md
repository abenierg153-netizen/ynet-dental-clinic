# Yanet Dental Clinic Website

A professional, responsive dental clinic website built with HTML, TailwindCSS, and modern web technologies. Optimized for Vercel deployment with comprehensive analytics, SEO, and PWA features.

## 🚀 Quick Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/yanet-dental-clinic)

## 📋 Features

### Core Features
- **Responsive Design**: Mobile-first approach with desktop optimization
- **Multi-page Structure**: Home, Services, Community, Book Now, Blogs
- **Clean URLs**: SEO-friendly routing without .html extensions
- **Fast Loading**: Optimized images, fonts, and caching strategies

### Analytics & Tracking
- **Google Analytics 4**: Complete traffic and conversion tracking
- **Meta Pixel**: Facebook/Instagram ad optimization
- **TikTok Pixel**: TikTok campaign tracking
- **Cookie Consent**: GDPR-compliant privacy management

### SEO & Performance
- **Meta Tags**: Comprehensive SEO optimization
- **Open Graph**: Social media sharing optimization
- **Structured Data**: Schema.org markup for rich snippets
- **Sitemap**: XML sitemap for search engines
- **PWA Support**: Progressive Web App capabilities

### Interactive Features
- **Appointment Booking**: Form validation and backend integration
- **Community Hub**: Smile Quiz, Cost Estimator, Virtual Consultation
- **Blog System**: Category filtering and newsletter signup
- **Rewards Club**: Customer loyalty program

## 🛠️ Local Development

### Prerequisites
- Node.js 18+ (for Vercel CLI)
- Git

### Setup
```bash
# Clone the repository
git clone https://github.com/your-username/yanet-dental-clinic.git
cd yanet-dental-clinic

# Install Vercel CLI
npm install -g vercel

# Start development server
npm run dev
# or
vercel dev
```

### Available Scripts
- `npm run dev` - Start local development server
- `npm run build` - Build for production (static site)
- `npm run start` - Start production server
- `npm run deploy` - Deploy to Vercel production
- `npm run preview` - Preview deployment

## 🌐 Deployment

### Vercel Deployment
1. **Connect Repository**: Link your GitHub repository to Vercel
2. **Configure Domain**: Set up your custom domain (yanetdental.com)
3. **Environment Variables**: Add analytics IDs:
   - `GA_MEASUREMENT_ID` - Google Analytics 4 ID
   - `META_PIXEL_ID` - Facebook Pixel ID
   - `TIKTOK_PIXEL_ID` - TikTok Pixel ID
4. **Deploy**: Automatic deployment on git push

### Manual Deployment
```bash
# Install Vercel CLI
npm install -g vercel

# Login to Vercel
vercel login

# Deploy
vercel --prod
```

## 📁 Project Structure

```
yanet-dental-clinic/
├── index.html              # Homepage
├── services.html           # Services page
├── community.html          # Community hub
├── book-now.html          # Appointment booking
├── blogs.html             # Blog overview
├── 404.html               # Custom 404 page
├── 500.html               # Custom 500 page
├── vercel.json            # Vercel configuration
├── package.json           # Project metadata
├── sitemap.xml            # SEO sitemap
├── robots.txt             # Search engine directives
├── site.webmanifest       # PWA manifest
└── README.md              # This file
```

## ⚙️ Configuration

### Analytics Setup
Replace placeholder IDs in all HTML files:
- `GA_MEASUREMENT_ID` → Your Google Analytics 4 ID
- `META_PIXEL_ID` → Your Facebook Pixel ID
- `TIKTOK_PIXEL_ID` → Your TikTok Pixel ID

### Form Backend
Update form actions in:
- `book-now.html`: Replace Formspree URL with your backend
- `blogs.html`: Replace newsletter service with your provider

### Domain Configuration
Update all references to `yanetdental.com` with your actual domain.

## 🔧 Customization

### Colors & Branding
Update CSS variables in all HTML files:
- `dental-blue`: #3B82F6 (primary blue)
- `dental-gold`: #F59E0B (accent gold)

### Content Updates
- **Services**: Update service descriptions in `services.html`
- **Blog Posts**: Add new articles in `blogs.html`
- **Team**: Update doctor profiles in `index.html`
- **Contact**: Update contact information across all pages

## 📊 Analytics Events

### Conversion Tracking
- `Book_Appointment` - Appointment form submission
- `Newsletter_Signup` - Newsletter subscription
- `Smile_Quiz_Completed` - Quiz completion
- `Cost_Estimator_Used` - Cost calculation usage
- `Virtual_Consultation_Submitted` - Consultation request
- `Rewards_Club_Signup` - Rewards program signup

### Engagement Tracking
- `Blog_Article_View` - Blog post views
- `Page_View` - Standard page views
- `Form_Interaction` - Form field interactions

## 🔒 Security & Privacy

### Security Headers
- HTTPS enforcement
- XSS protection
- Content type sniffing prevention
- Frame options protection
- Strict transport security

### Privacy Compliance
- GDPR-compliant cookie consent
- Data minimization practices
- User control over tracking
- Transparent privacy policies

## 🚀 Performance Optimizations

### Caching Strategy
- Static assets: 1 year cache
- HTML pages: 1 hour cache
- Sitemap/Robots: 24 hour cache

### Loading Optimizations
- Font preloading
- Async script loading
- Image optimization
- CSS optimization

## 📱 PWA Features

### App-like Experience
- Installable on mobile devices
- Offline capability
- App icons for all platforms
- Splash screen support

### Manifest Configuration
- App name and description
- Theme colors
- Icon sizes
- Display modes

## 🆘 Support & Maintenance

### Regular Updates
- Update analytics IDs as needed
- Refresh blog content monthly
- Update service information quarterly
- Review and update contact information

### Monitoring
- Monitor analytics dashboards
- Track conversion rates
- Review error logs
- Check page speed scores

## 📞 Contact

For technical support or customization requests:
- **Email**: tech@yanetdental.com
- **Phone**: +1-555-123-4567
- **Website**: https://yanetdental.com

---

**Built with ❤️ for Yanet Dental Clinic**
