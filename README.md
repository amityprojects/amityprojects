# Amity Project — Report Writing Help

[![Live Site](https://img.shields.io/badge/live-amityprojects.online-2563eb)](https://www.amityprojects.online/)
[![Next.js](https://img.shields.io/badge/Next.js-14-black)](https://nextjs.org/)
[![License](https://img.shields.io/badge/license-Private-lightgrey)]()

> Marketing website for **Amity Project** — an independent academic writing-help service for Amity University students (MBA, BBA, BA, BCA, BCOM, MCOM, MA, PGDPA).

🔗 **Live:** https://www.amityprojects.online/

---

## ✨ Overview

This repo contains the source for the Amity Project marketing site — a fast, SEO-optimized, conversion-focused landing experience built to:

- Showcase course-specific project/dissertation help (MBA, BBA, BA, BCA, BCOM, MCOM, MA, PGDPA)
- Explain pricing, process ("How it works"), and sample deliverables
- Route leads to WhatsApp / phone for quotes
- Rank well in search for course-specific queries (e.g. "Amity MBA project help")

## 🧱 Tech Stack

| Layer | Choice |
|---|---|
| Framework | Next.js (App Router) |
| Styling | Tailwind CSS |
| Hosting | Vercel (or similar) |
| Lead capture | WhatsApp deep links (`wa.me`) + tel links |
| SEO | Static metadata, OG/Twitter images, sitemap |

## 📁 Project Structure

```
.
├── app/
│   ├── page.tsx                 # Home page
│   ├── how-it-works/page.tsx
│   ├── samples/page.tsx
│   ├── pricing/page.tsx
│   ├── faq/page.tsx
│   ├── about/page.tsx
│   ├── contact/page.tsx
│   ├── [course]-project/page.tsx   # mba, bba, ba, bca, bcom, mcom, ma, pgdpa
│   ├── qollabb-project-work/page.tsx
│   ├── synopsis-writing/page.tsx
│   ├── assignments/page.tsx
│   ├── disclaimer/page.tsx
│   ├── privacy/page.tsx
│   └── terms/page.tsx
├── components/
│   ├── Hero.tsx
│   ├── CourseGrid.tsx
│   ├── PricingCards.tsx
│   ├── Testimonials.tsx
│   ├── FAQAccordion.tsx
│   └── Footer.tsx
├── public/
│   └── opengraph-image.png
├── styles/
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 18
- npm / pnpm / yarn

### Installation

```bash
git clone https://github.com/<your-org>/amity-project-site.git
cd amity-project-site
npm install
```

### Local Development

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000).

### Build & Production

```bash
npm run build
npm run start
```

## ⚙️ Environment Variables

Create a `.env.local`:

```env
NEXT_PUBLIC_SITE_URL=https://www.amityprojects.online
NEXT_PUBLIC_WHATSAPP_NUMBER=917676409450
NEXT_PUBLIC_CONTACT_PHONE=+917676409450
```

## 🧩 Key Sections (Home Page)

1. **Hero** — value prop, trust badges, primary CTA (WhatsApp / call)
2. **Stats bar** — years active, reports delivered, plagiarism-free %, starting price
3. **Course grid** — MBA / BBA / BA / BCA / BCOM / MCOM / MA / PGDPA
4. **Why us** — researched-not-recycled, guideline-aligned, plagiarism checks, free revisions
5. **Report anatomy** — 9-chapter breakdown (Abstract → Bibliography & Annexure)
6. **Process** — 5-step flow from inquiry to delivery
7. **Pricing** — Minor Project / Project Report / Dissertation tiers
8. **Testimonials**
9. **FAQ**
10. **Final CTA + Footer** (legal links, disclaimer, course links)

## 🔍 SEO Notes

- Canonical: `https://www.amityprojects.online`
- OG/Twitter image served at `/opengraph-image`
- Locale: `en_IN`
- Each course page (`/mba-project`, `/bba-project`, etc.) targets its own keyword cluster

## 📜 Legal / Disclaimer

Amity Project is an **independent** service and is **not affiliated with, endorsed by, or connected to Amity University**. "Amity" is used descriptively only. Content is provided for reference and learning support — see `/disclaimer`, `/privacy`, and `/terms` for full policies.

## 🤝 Contributing

This is a private/commercial site repo. For internal contributors:

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Commit with clear messages
3. Open a PR against `main`

## 📞 Contact

- WhatsApp: [+91 76764 09450](https://wa.me/917676409450)
- Phone: +91 76764 09450

---

© 2026 Amity Project. All rights reserved.
