# CT Demo Website

Client-facing demo inspired by [ct.com.au](https://ct.com.au) (Centorrino Technologies).

## Local preview

```bash
npm start
```

Open [http://localhost:5173](http://localhost:5173). Or open `index.html` directly in a browser.

## Deploy to Vercel

**Option A — Dashboard**
1. Push this folder to GitHub
2. Import the repo at [vercel.com/new](https://vercel.com/new)
3. Framework: **Other** · Build command: leave empty · Output: `.`
4. Deploy

**Option B — CLI**
```bash
npx vercel
```
Follow the prompts, then `npx vercel --prod` for production.

## Deploy to Netlify

**Option A — Dashboard**
1. Push this folder to GitHub
2. Import at [app.netlify.com](https://app.netlify.com)
3. Build command: leave empty (or use the one in `netlify.toml`) · Publish directory: `.`
4. Deploy

**Option B — Drag & drop**
Zip the project (or drag the folder) into [app.netlify.com/drop](https://app.netlify.com/drop).

**Option C — CLI**
```bash
npx netlify deploy
npx netlify deploy --prod
```

## What's included

- Homepage matching CT’s story and dark tech aesthetic
- Discovery-session contact modal
- `vercel.json` + `netlify.toml` ready for both hosts
- Clear **CLIENT DEMO** banner

## Note

Independent concept for demo purposes — not affiliated with Centorrino Technologies.
