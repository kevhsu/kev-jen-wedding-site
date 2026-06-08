# Kev and Jen's Wedding Site

A very small static wedding information site for the June 19-21, 2026 wedding
weekend.

## Files

- `index.html` contains the page content and event information.
- `styles.css` contains the responsive layout and visual styling.
- `assets/wedding-weekend-photo-upright.jpg` is the hero/background image used by the
  page.

## Preview Locally

From this folder:

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4173/
```

## Deploy

This is a static site with no build step. Deploy the repository root to any
static host, such as GitHub Pages, Netlify, Vercel, Cloudflare Pages, or an S3
bucket.

The entry file is:

```text
index.html
```
