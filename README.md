# Dr. Sumreen Asim — Personal Website

A single-page site for Dr. Sumreen Asim, Professor of Science and Technology Education at Indiana University Southeast.

It's a static site with no build step. Everything, including the images, is inside `index.html`.

- `index.html` — the website
- `vercel.json` — hosting settings for Vercel
- `docs/content.md` — all site text in one place
- `docs/aesthetic.md` — colors, fonts, layout, and animation notes

## Deploy on Vercel

1. Go to https://vercel.com/new and import this GitHub repository.
2. Set the framework preset to **Other**. Leave the build command empty and the output directory as the default.
3. Click **Deploy**.

Every push to `main` redeploys the site automatically.

## Preview locally

Open `index.html` in a browser, or run:

```
npx serve .
```
