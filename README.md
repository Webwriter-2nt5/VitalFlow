# VitalFlow — AI-Powered Health Tech Portfolio

A production-grade Next.js 14 website showcasing VitalFlow's health tech solutions with modern design patterns, smooth animations, and enterprise-grade performance.

## 🚀 Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS + Custom CSS Variables
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Typography**: Syne (Display) + DM Sans (Body) from Google Fonts
- **Deployment**: Vercel-ready

## 📁 Project Structure

```
vitalflow/
├── app/
│   ├── layout.tsx              # Root layout with metadata
│   ├── globals.css             # Global styles & design tokens
│   ├── page.tsx                # Home page
│   ├── about/page.tsx          # About page
│   ├── services/page.tsx       # Services page
│   ├── case-studies/page.tsx   # Case studies page
│   └── contact/page.tsx        # Contact page
├── components/
│   ├── shared/
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   ├── GlassCard.tsx
│   │   ├── AnimatedSection.tsx
│   │   └── StatBadge.tsx
│   ├── home/
│   │   ├── HeroSection.tsx
│   │   └── FeatureCard.tsx
│   ├── about/
│   │   ├── MissionQuote.tsx
│   │   ├── Timeline.tsx
│   │   └── TeamCard.tsx
│   ├── services/
│   │   └── ProductPanel.tsx
│   ├── case-studies/
│   │   └── CaseStudyCard.tsx
│   └── contact/
│       └── ContactForm.tsx
├── public/                      # Static assets
├── package.json
├── tsconfig.json
├── tailwind.config.ts
├── next.config.js
└── postcss.config.js
```

## 🎨 Design System

### Colors (CSS Variables)
```css
--color-bg:      #0a0f1e (Deep Navy)
--color-surface: #131928 (Surface)
--color-border:  #1e2a3a (Border)
--color-accent:  #00e5cc (Teal - Primary)
--color-purple:  #7c3aed (Purple - Secondary)
--color-coral:   #ff6b6b (Coral - Error)
--color-text:    #f0f4ff (Text)
--color-muted:   #8899aa (Muted Text)
```

### Typography
- **Display**: Syne (700 weight) — Headlines
- **Body**: DM Sans (400/500 weight) — Body text
- **Mono**: JetBrains Mono (500 weight) — Technical elements

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Webwriter-2nt5/VitalFlow.git
cd vitalflow

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🌐 Pages

| Route | Description |
|-------|-------------|
| `/` | Home with hero section and features |
| `/about` | Mission, timeline, and team |
| `/services` | Product panels for VitalScan, CareFlow, PulseAlert |
| `/case-studies` | Portfolio of real projects |
| `/contact` | Contact form with validation |

## ✨ Features

- ✅ **Responsive Design** — Mobile-first approach with Tailwind CSS
- ✅ **Dark Mode** — Built-in with CSS variables
- ✅ **Smooth Animations** — Framer Motion scroll triggers and page transitions
- ✅ **Form Validation** — Client-side validation with error messages
- ✅ **Glassmorphism** — Modern UI glass effects with backdrop blur
- ✅ **Accessibility** — ARIA labels, focus states, semantic HTML
- ✅ **SEO** — Meta tags, Open Graph, Twitter Card
- ✅ **Performance** — Image optimization, code splitting, lazy loading
- ✅ **TypeScript** — Strict mode for type safety

## 🎬 Animations

- Page fade-in on load
- Scroll-triggered card reveals with stagger
- Navbar blur on scroll
- Hero dashboard float animation
- Button scale on hover
- Timeline dot connectors

## 📱 Mobile Optimization

- Hamburger menu with slide drawer
- Touch-friendly button sizes
- Optimized typography scales
- Responsive grid layouts
- Mobile-first CSS approach

## 🚀 Deployment

### Vercel (Recommended)
```bash
vercel deploy
```

### Manual Deployment
```bash
npm run build
npm start
```

## 📝 Environment Variables

Create `.env.local`:
```env
NEXT_PUBLIC_SITE_URL=https://vitalflow.io
```

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

## 🎯 Performance Targets

- Lighthouse Score: 90+
- Core Web Vitals: All Green
- Bundle Size: < 500KB
- First Contentful Paint: < 1.5s

## 📧 Contact

For inquiries, visit [/contact](/contact) or email hello@vitalflow.io

---

**Made with ❤️ for the future of healthcare.**
