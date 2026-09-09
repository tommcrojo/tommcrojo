# tomcrojo.com

Personal reputation and technical portfolio site for **Tomás Campoy Rojo**, Data Engineer at UCAM.

The site is deliberately built as a static Astro project: fast HTML, crawlable content, stable URLs, structured metadata and minimal client-side JavaScript.

## Information architecture

- `/` — positioning, evidence and featured work
- `/about` — professional bio and technical focus
- `/work` — professional case studies, including public-safe UCAM work
- `/projects` — public GitHub projects
- `/writing` — technical articles derived from implemented projects and measured engineering work

## GEO / SEO decisions

- Canonical identity is `Tomás Campoy Rojo`.
- `Data Engineer`, `UCAM` and `Universidad Católica San Antonio de Murcia` are stated together in crawlable HTML.
- `Person` JSON-LD links the website, UCAM, GitHub and LinkedIn.
- Pages are static and readable without JavaScript.
- `robots.txt` explicitly allows `OAI-SearchBot`.
- `llms.txt` provides a compact machine-readable description and section map.
- Case studies use stable, descriptive URLs and self-contained introductions.

## Local development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## Deployment

Point `tomcrojo.com` at the static deployment of this repository (Vercel, Cloudflare Pages, Netlify, GitHub Pages, etc.). The canonical site URL is configured in `astro.config.mjs`.

## Editorial rule

Professional case studies should include only information that is safe to make public. Avoid internal credentials, schemas, personal data, proprietary source code, confidential metrics, and claims that cannot be defended with evidence.
