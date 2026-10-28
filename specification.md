# Portfolio specification
Purpose: introduce Nebraas Sattar to recruiters through verified engineering work. Success means clear project access, accessible mobile layouts, a public-safe resume, and reproducible builds.

Sources: supplied Synchrony resume (BS Engineering, Computer Science and Engineering, UConn, expected May 2027; GPA 3.636 in this supplied copy); math-practice-app source at supplied GitHub remote. Do not infer a newer GPA. Professional email: nesattar786@hotmail.com. GitHub: nebraassattar. No LinkedIn supplied. Omit phone and location from public resume.

Structure: single-page navigation to Work, About, Experience, Contact; hero with View Projects and View Resume; featured math case study; four resume projects; education, grouped skills, work experience; email contact.

Design: warm ivory, ink, forest green; editorial serif display with system sans text; generous spacing, restrained borders, responsive two-column desktop and stacked mobile. Semantic landmarks, skip link, visible focus, reduced-motion support, no stock images or tracking.

Architecture: React + TypeScript + Vite, plain CSS, typed content file. No backend, form, account, analytics, or client routing. Images have dimensions; downloadable resume excludes unnecessary personal information. Metadata, favicon; canonical/sitemap only once hosting URL is verified.

Math case study: ages 7–12; four operations and difficulty settings; self-reported answer results, browser-local statistics, mistake review, session recovery. Verify deployed appearance and capture a real screenshot. Explain bounded generators, validated versioned storage, derived statistics and recovery. Label future improvements separately; no usage metrics.

Delivery: supplied empty personal_portfolio GitHub repository; meaningful commits, no force pushes; Actions lint/typecheck/build; Netlify-compatible static configuration. Prefer public recruiter-accessible hosting connected to main. Hosting identity and authentication are unresolved until inspected.

Acceptance: production build, lint and typecheck pass; desktop/mobile and keyboard review; links/assets work; no observed console errors; privacy review; pushed commit and reachable deployment verified before marking complete.

Implementation status (2026-10-28): responsive site implemented, verified build and public-safe resume generated. See VERIFICATION.md. The supplied GPA is retained in the resume only; no newer value inferred. GitHub push verified. Existing Netlify account discovered; app integration currently exposes only math repository. User repository-access change is the remaining connected deployment blocker.
