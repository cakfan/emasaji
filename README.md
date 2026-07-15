# EmasAji — Landing Page

Landing page untuk **EmasAji Kursus Mengemudi & Biro Jasa** di Jember, Jawa Timur.

Built with [Astro](https://astro.build/) · Deployed to [GitHub Pages](https://cakfan.github.io/emasaji/)

## Tech Stack

- **Framework**: Astro 7.x (static output)
- **Fonts**: Clash Display + General Sans via [Fontshare](https://fontshare.com)
- **Deployment**: GitHub Pages (`gh-pages` branch)

## Getting Started

```bash
npm install
npm run dev
```

Open `http://localhost:4321` in your browser.

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server |
| `npm run build` | Build to `docs/` |
| `npm run preview` | Preview production build |

## Project Structure

```
src/
├── components/
│   ├── Header.astro      # Sticky navbar + hamburger menu
│   ├── Hero.astro         # Hero section with speedometer gauge
│   ├── TrustBar.astro     # Trust indicators bar
│   ├── Services.astro     # Service cards
│   ├── WhyUs.astro        # Why choose us section
│   ├── Testimonials.astro # Student testimonials
│   ├── Pricing.astro      # Pricing cards
│   ├── Location.astro     # Google Maps embed + contact info
│   ├── FAQ.astro          # Accordion FAQ
│   └── Footer.astro       # Site footer
├── layouts/
│   └── Layout.astro       # Base HTML layout + SEO meta
├── pages/
│   └── index.astro        # Homepage
├── data/
│   └── site.json          # All content & business data
└── styles/
    └── global.css         # Design tokens + base styles
```

## Key Features

- Speedometer gauge animation (5-gear shift)
- Scroll-reveal animations with `IntersectionObserver`
- Responsive mobile nav with hamburger menu
- WhatsApp click-to-chat CTAs
- Google Maps embed with business info
- SEO optimized (LD+JSON structured data, Open Graph, Twitter Card)
- Accessible (skip-link, ARIA labels, `prefers-reduced-motion` support)

## Deployment

Build output goes to `docs/`. The `gh-pages` branch contains only the production build with `.nojekyll`.

```bash
npm run build
# Copy docs/* to gh-pages branch, commit, push
```

## License

Private — EmasAji Kursus Mengemudi Jember.
