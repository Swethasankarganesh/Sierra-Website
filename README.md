# Sierra Digital website (Next.js 15 · TypeScript · Tailwind 4)
npm install && npm run dev   |   npm run build && npm start
- Content lives in `data/` (solutions, services, products, industries, processes, insights, testimonials, navigation).
- Logo + product pages load from sierradigitalinc.com. To self-host the logo, save it to `public/` and edit `data/site.ts` (LOGO).
- Photos: 4 real photos are hotlinked live from images.unsplash.com (see components/Photo.tsx REAL_PHOTOS); the remaining industry/solution tiles use local WebP (public/images/) or a live animated SVG diagram (components/LiveDiagram.tsx) for abstract "cloud/data" concepts.
- Contact form: set `CONTACT_WEBHOOK_URL` (POST JSON). Without it the form shows an error instead of faking success.
- Set `NEXT_PUBLIC_SITE_URL` for canonical URLs and the sitemap.
