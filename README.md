# tomcrojo.com

Personal website and technical portfolio for **Tomás Campoy Rojo**.

The site is designed as a public proof layer around my work in **data engineering, data platforms, AI systems, cloud architecture, automation, performance and reliability**.

## Structure

- `/` — positioning, selected outcomes and paths to work together
- `/work` — professional case studies and measurable operational improvements
- `/projects` — public engineering projects
- `/writing` — technical notes on data platforms, AI infrastructure and systems reliability
- `/about` — background, technical focus and current interests

## Technical direction

The site is intentionally static and crawlable. It uses Astro with canonical URLs, structured `Person` metadata, `robots.txt` and `llms.txt` so the same public evidence is legible to people, search engines and AI retrieval systems.

## Selected public work

- [AWS GDPR-Compliant Healthcare Pipeline](https://github.com/tomcrojo/aws-gdpr-healthcare-pipeline)
- [Azure Medallion Pipeline](https://github.com/tomcrojo/azure-medallion-pipeline)
- [Streaming Orders Pipeline](https://github.com/tomcrojo/streaming-orders-pipeline)
- [Student Data Pipeline](https://github.com/tomcrojo/student-data-pipeline)
- [Pandas → Polars Migration Command](https://github.com/tomcrojo/pandas-polars-migration-claude)
- [Security Log Analytics](https://github.com/tomcrojo/security-log-analytics)

## GEO / discovery decisions

- Canonical identity is `Tomás Campoy Rojo`.
- The primary entity relationship is Tomás → data engineering / data platforms / AI systems; employer context is supporting evidence rather than the center of the brand.
- `Person` JSON-LD links the website, current employer, GitHub and LinkedIn and declares the relevant technical domains.
- Pages are static and readable without JavaScript.
- `robots.txt` explicitly allows `OAI-SearchBot`.
- `llms.txt` provides a compact machine-readable description, topic map and selected writing.
- Case studies and essays use stable descriptive URLs and self-contained introductions.

## Development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

## Editorial rule

Professional case studies should include only information that is safe to make public. Avoid internal credentials, schemas, personal data, proprietary source code, confidential metrics, and claims that cannot be defended with evidence.

Canonical domain: [tomcrojo.com](https://tomcrojo.com)
