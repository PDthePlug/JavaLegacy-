# Java Legacy Funerals — Website & Review PWA

Production-candidate frontend for Java Legacy Funerals, built as a responsive React/Vite site and installable Progressive Web App (PWA).

## Included

- Funeral-cover discovery and guided quote journey
- Immediate bereavement assistance flow
- Funeral-services enquiry flow
- Church & community partnership enquiry
- WhatsApp, phone and email handoffs
- Product education, FAQ and regulatory disclosures
- SEO/social metadata and structured data
- Responsive mobile experience
- PWA manifest, branded icon and service worker

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## PWA

The app includes `public/manifest.webmanifest`, `public/pwa-icon.svg` and `public/sw.js`. The service worker is registered from `src/main.tsx`.

## Important product-content note

Published premiums, benefits, waiting periods, eligibility, exclusions, underwriting relationships and other regulated product claims must remain aligned with Java Legacy Funerals' approved quotation and policy documentation.

## Stack

React 19 · TypeScript · Vite · Tailwind CSS · Lucide React
