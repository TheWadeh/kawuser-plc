![Kawser PLC - Building Trust Across Industries](./public/images/kawser-hero.jpg)

# Kawser PLC - Corporate Website

A modern, professional corporate website for Kawser PLC, a diversified Ethiopian business group with over 20 years of experience across retail, minerals, machinery, logistics, and large-scale trade.

## 🌟 Features

- **Modern Design**: Clean, professional UI with navy blue and gold color scheme
- **Fully Responsive**: Mobile-first design that works seamlessly across all devices
- **Fast Performance**: Optimized build with code splitting and lazy loading
- **SEO Optimized**: Comprehensive meta tags, structured data, and sitemap
- **Interactive Components**: Smooth animations and transitions using Framer Motion
- **Comprehensive Sections**:
  - Hero section with company overview
  - Business sectors showcase
  - Heavy machinery and vehicle rental gallery
  - Company timeline and history
  - Mission, vision, and values
  - Leadership information
  - Media gallery
  - Contact information

## 🚀 Tech Stack

- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite with optimized configuration
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Animations**: Framer Motion
- **Routing**: React Router DOM with lazy loading
- **Icons**: Lucide React
- **State Management**: TanStack Query

## ⚡ Performance Optimizations

### Build Optimizations
- ✅ Code splitting with manual chunks
- ✅ Route-based lazy loading with React.lazy()
- ✅ Terser minification with console.log removal
- ✅ Tree shaking for unused code
- ✅ Optimized vendor bundles (react, ui, radix)
- ✅ React SWC for faster compilation

### Image Optimizations
- ✅ Lazy loading with Intersection Observer
- ✅ Priority loading for hero images
- ✅ Proper alt tags for SEO and accessibility
- ✅ OptimizedImage component

### Caching Strategy
- ✅ Static assets cached for 1 year
- ✅ Images with immutable flag
- ✅ HTML no-cache for fresh content
- ✅ Service worker ready

### SEO Enhancements
- ✅ Comprehensive meta tags (Open Graph, Twitter Cards)
- ✅ Structured data (JSON-LD) for Organization
- ✅ XML sitemap with all routes
- ✅ Robots.txt for crawlers
- ✅ Canonical URLs
- ✅ Geo-targeting for Ethiopia
- ✅ Dynamic SEO component

### Security
- ✅ Security headers (X-Frame-Options, CSP, etc.)
- ✅ HTTPS redirect configuration
- ✅ XSS protection

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd kawserplc
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:8080`

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production (optimized)
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run test` - Run tests
- `npm run test:watch` - Run tests in watch mode

## 📊 Build Output

Production build generates optimized bundles:
- **Initial bundle**: ~160KB (gzipped: ~52KB)
- **UI vendor**: ~133KB (gzipped: ~44KB)
- **Radix vendor**: ~38KB (gzipped: ~14KB)
- **CSS**: ~77KB (gzipped: ~13KB)
- **Route chunks**: 0.5-25KB each (lazy loaded)

## 📁 Project Structure

```
kawser-trust/
├── public/
│   ├── images/
│   │   ├── machinery/      # Heavy equipment images
│   │   └── for rent/       # Vehicle rental images
│   ├── sitemap.xml         # SEO sitemap
│   ├── robots.txt          # Crawler instructions
│   ├── _headers            # Netlify headers
│   ├── .htaccess           # Apache configuration
│   └── favicon.svg
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── ui/            # shadcn/ui components
│   │   ├── SEO.tsx        # Dynamic SEO component
│   │   ├── OptimizedImage.tsx  # Lazy loading images
│   │   ├── Hero.tsx
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   └── ...
│   ├── pages/             # Page components (lazy loaded)
│   │   ├── Index.tsx
│   │   ├── About.tsx
│   │   ├── Business.tsx
│   │   ├── Machinery.tsx
│   │   └── ...
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility functions
│   │   ├── performance.ts # Performance monitoring
│   │   └── preload.ts     # Resource preloading
│   ├── App.tsx            # Route configuration
│   ├── main.tsx
│   └── index.css
├── PERFORMANCE.md         # Performance guide
├── SEO_CHECKLIST.md       # SEO implementation checklist
├── index.html             # Enhanced with SEO meta tags
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts         # Optimized build config
```

## 🎨 Design System

### Colors
- **Primary**: Navy Blue (#3b82f6)
- **Secondary**: Gold (#fbbf24)
- **Background**: White / Slate for dark sections

### Typography
- **Headings**: Bold, tracking-tight
- **Body**: Regular weight, relaxed line-height

## 🖼️ Image Assets

The project uses real images for:
- 5 Heavy machinery items (bulldozer, excavator, grader, crane, low bed truck)
- 3 Vehicle rentals (Land Cruiser models)

All images are located in `/public/images/`

## 📱 Mobile Optimization

- ✅ Mobile-first responsive design
- ✅ Fixed horizontal scrolling issues
- ✅ Touch-friendly navigation with hamburger menu
- ✅ Optimized images and performance
- ✅ Smooth scrolling and animations
- ✅ No overflow issues

## 🌐 Pages

1. **Home** - Overview with hero, stats, about snapshot, business cards, machinery showcase
2. **About** - Company history, mission, vision, values, timeline
3. **Leadership** - Founder profile and organizational structure
4. **Business** - Business sectors and services
5. **Machinery** - Equipment and vehicle rental showcase
6. **Media** - Image gallery
7. **Contact** - Contact information and form
8. **Careers** - Job opportunities
9. **HSE** - Health, Safety & Environment policy
10. **Legal** - Legal information and certifications

## 🔍 SEO Features

- **Meta Tags**: Complete set for search engines and social media
- **Structured Data**: JSON-LD Organization schema
- **Sitemap**: XML sitemap at `/sitemap.xml`
- **Robots.txt**: Crawler instructions at `/robots.txt`
- **Canonical URLs**: Prevent duplicate content
- **Open Graph**: Rich social media previews
- **Twitter Cards**: Enhanced Twitter sharing
- **Geo-targeting**: Ethiopia-specific meta tags

## 📈 Performance Monitoring

### Tools to Use
1. **Google PageSpeed Insights** - https://pagespeed.web.dev/
2. **Lighthouse** - Built into Chrome DevTools
3. **WebPageTest** - https://www.webpagetest.org/
4. **GTmetrix** - https://gtmetrix.com/

### Target Metrics
- **Lighthouse Performance**: 90+
- **LCP (Largest Contentful Paint)**: <2.5s
- **FID (First Input Delay)**: <100ms
- **CLS (Cumulative Layout Shift)**: <0.1

## 🔧 Configuration

### Tailwind CSS
Custom configuration in `tailwind.config.ts` with extended color palette and custom utilities.

### Vite
Optimized build configuration in `vite.config.ts`:
- Manual chunk splitting
- Terser minification
- Dependency optimization
- Source map configuration

### TanStack Query
Configured with:
- 5-minute stale time
- 10-minute garbage collection
- No refetch on window focus

## 🚀 Deployment

### Pre-deployment Checklist
- [ ] Update domain in `sitemap.xml`
- [ ] Update domain in `index.html` meta tags
- [ ] Run `npm run build` and verify output
- [ ] Test production build with `npm run preview`
- [ ] Run Lighthouse audit
- [ ] Test on mobile devices
- [ ] Verify all routes work
- [ ] Check robots.txt is accessible

### Deployment Platforms
- **Netlify**: Automatic deployment with `_headers` support
- **Vercel**: Zero-config deployment
- **Apache**: Use `.htaccess` for configuration
- **Nginx**: Configure caching and compression

### Post-deployment
1. Submit sitemap to Google Search Console
2. Submit sitemap to Bing Webmaster Tools
3. Set up Google Analytics (optional)
4. Monitor performance with Lighthouse
5. Check mobile responsiveness

## 📄 Documentation

- **PERFORMANCE.md** - Detailed performance optimization guide
- **SEO_CHECKLIST.md** - Complete SEO implementation checklist

## 📄 License

© 2024 Kawser PLC. All rights reserved.

## 🤝 Contributing

This is a private corporate website. For any inquiries, please contact Kawser PLC directly.

## 📞 Contact

- **Phone**: +251 11 552 7691 / 84
- **Email**: kawuserplc97@yahoo.com
- **Location**: Addis Ababa, Ethiopia

---

Built with ❤️ for Kawser PLC
