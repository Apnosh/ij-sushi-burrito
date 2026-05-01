# IJ Sushi Burrito

Static marketing site for IJ Sushi Burrito — Japanese-Hawaiian fusion. Sushi burritos, poké bowls, salad bowls. 13+ locations across WA, OR, CA & NJ.

## Pages

- `index.html` — Home
- `menu.html` — Full menu (signature, BYO, poké, salad, sides, drinks, catering)
- `locations.html` — All 13+ locations
- `about.html` — Brand story
- `gift-cards.html` — Digital gift card promo
- `contact.html` — Contact form + email

## Stack

Pure static HTML / CSS. No build step. Each page has scoped inline `<style>` for page-specific styles plus a shared `styles.css` for global tokens, nav, footer, buttons.

## Deploy (Vercel)

```bash
# one-time
npm i -g vercel

# deploy
vercel        # preview
vercel --prod # production
```

Or push to GitHub and connect the repo at [vercel.com/new](https://vercel.com/new).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
