# Eli & Co. Aesthetics

Marketing website for **Eli & Co. Aesthetics**, a Cherry Creek med spa in Denver, CO led by Elizabeth Dozal.

A static, multi-page site built with plain HTML and CSS — no build step required.

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| About & Team | `about.html` |
| Services & Packages | `services.html` |
| Memberships | `memberships.html` |
| Contact | `contact.html` |

Shared styling lives in `styles.css`. Fonts are loaded from Google Fonts (Cormorant Garamond + Jost).

## Running locally

It's a static site, so just open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000.

## Deploying

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For **GitHub Pages**, enable Pages in the repo settings and serve from the `main` branch root.

---

Contact: 720-934-6167 · 44 Cook St, Suite 200, Denver, CO 80206 · [Book online](https://eliandco.glossgenius.com/services)
