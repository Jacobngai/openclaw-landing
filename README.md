# OpenClaw Landing Page

AI Setup Service by Result Marketing

## Brand

- **Domain:** openclaw.resultmarketing.asia
- **Mascot:** 🦞 Lobster
- **Colors:** Lobster red (#ff4444) + Ocean blue (#0ea5e9)

## Tech Stack

- Astro 4
- Tailwind CSS
- i18n (EN, BM, ZH)

## Development

```bash
npm install
npm run dev
```

## Deploy

Deploy to Vercel with domain: `openclaw.resultmarketing.asia`

## Structure

```
src/
├── i18n/
│   └── translations.js    # All translations
├── layouts/
│   └── BaseLayout.astro   # Shared layout with brand bar
├── pages/
│   ├── index.astro        # Redirect to /en
│   ├── en/index.astro     # English landing
│   ├── ms/index.astro     # Malay landing
│   └── zh/index.astro     # Chinese landing
└── styles/
    └── global.css         # Tailwind + custom styles
```

## Related Brands

| Brand | Domain | Mascot |
|-------|--------|--------|
| AIEO | seo.resultmarketing.asia | 🟣 Purple |
| OpenClaw | openclaw.resultmarketing.asia | 🦞 Lobster |
| Result Tech | tech.resultmarketing.asia | 🐙 Octopus |
