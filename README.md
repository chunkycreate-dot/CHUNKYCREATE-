# ChunkyCreate
Dev: `npm install && npm run dev`   Build: `npm run build` (output: `dist`)
Products: edit ONLY `src/data/products.ts`. Cover images go in `public/products/`.
Backend (later): `functions/api/*` = Cloudflare Pages Functions. Secrets (Razorpay, R2) go in Pages > Settings > Environment variables. Never commit PDFs.
Deploy: Cloudflare Pages > connect GitHub repo > Build command `npm run build` > Output dir `dist`.
