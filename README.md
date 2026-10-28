# Nebraas Sattar — Portfolio
React, TypeScript and Vite portfolio. Repository: https://github.com/nebraassattar/personal_portfolio

Use Node 24: `npm ci`, `npm run dev`. Checks: `npm run lint`, `npm run typecheck`, `npm run build`; preview: `npm run preview`.

Content lives in src/content.ts, layout in src/App.tsx, styles in src/style.css. Public assets live in public/. Update the public resume after removing phone/location and checking its contents. Add projects to the typed content array; include only verified facts and working links.

GitHub Actions checks every push and pull request. Netlify: import the supplied repository, branch main, build `npm run build`, publish `dist`; netlify.toml supplies defaults. Production URL and final verification status will be recorded after deployment.
