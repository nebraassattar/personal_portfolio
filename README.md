# Nebraas Sattar — Portfolio

Live: https://nebraas-sattar-portfolio.netlify.app/
Repository: https://github.com/nebraassattar/personal_portfolio

React, TypeScript and Vite. Use Node 24: `npm ci`, then `npm run dev`. Checks: `npm run lint`, `npm run typecheck`, `npm run build`. Production preview: `npm run preview`.

Content is in src/content.ts; section copy/layout in src/App.tsx; styles in src/style.css; static files in public/. Add future projects to the typed projects array with verified descriptions and technologies. Replace public/Nebraas-Sattar-Resume.pdf with your updated public-safe resume at the same path. Remove unnecessary personal details before committing and check the rendered PDF.

Netlify project: nebraas-sattar-portfolio (team nesattar786). Connected to nebraassattar/personal_portfolio, production branch main. Build command: npm run build. Publish directory: dist. Base and functions directories empty. netlify.toml selects Node 24. Pushes to main trigger automatic production deployments; GitHub Actions runs lint, typecheck and build. Check Actions and Netlify Deploys after updates.

Public launch verified 2026-10-28. Canonical metadata, robots.txt and sitemap.xml use the production URL. No backend, analytics, contact form, or secret is required. See specification.md, TODO.md and VERIFICATION.md for decisions and checks.
