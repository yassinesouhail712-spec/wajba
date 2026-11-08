# Wajba (وجبة)

Marketplace connecting Moroccan snacks and restaurants with customers. Orders are sent to the restaurant on WhatsApp.

- Frontend: React + Vite + Tailwind
- Backend: Google Apps Script Web App + Google Sheets (URL in `src/config.ts`)

## Run locally

```
npm install
npm run dev
```

## Deploy (free)

Connect this GitHub repository to **Cloudflare Pages**, **Netlify** or **Vercel**:

- Build command: `npm run build`
- Output directory: `dist`

`vercel.json` and `public/_redirects` already make deep links such as `/r/my-snack` and `/login` work.

## Backend

After any change to the Apps Script code: **Deploy > Manage deployments > Edit > New version > Deploy**.
