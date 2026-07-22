# NOTE LLC Website — Claude Code Instructions

## Project purpose
This repository is the official website for NOTE LLC (ノート合同会社), a Tokyo-based company working in event production, artist booking, international touring, record production, distribution, and tour mobility.

## Technical policy
- Keep the site as plain HTML, CSS, and vanilla JavaScript.
- Do not add npm, frameworks, build tools, or third-party JavaScript libraries unless the user explicitly requests them.
- The site must remain deployable directly through GitHub Pages.
- Preserve `CNAME` and the custom domain `www.note-llc.jp`.
- Keep all paths relative so the site works locally and on GitHub Pages.
- Use semantic HTML and progressive enhancement.
- JavaScript must not be required to read the content or use primary links.

## Design policy
- Direction: independent music label × production company; editorial, industrial, bold, restrained.
- Avoid generic startup/SaaS visuals, gradients, glassmorphism, excessive rounded cards, stock-photo aesthetics, and decorative animations.
- Main palette: near-black, warm off-white, white, and one signal red accent.
- Typography should use system fonts; do not introduce remote font dependencies without permission.
- Maintain strong hierarchy, generous whitespace, clear grid logic, and high contrast.

## Content policy
- Japanese is the primary language.
- English is used only for section labels and concise supporting copy.
- Do not publish unannounced releases, tours, artists, dates, prices, visa details, or private operational information.
- Do not invent Instagram URLs, project credits, release dates, company details, or client names.
- When uncertain about public status or factual data, ask before changing copy.
- Preserve the voice: direct, credible, independent, practical, and not overly corporate.

## Accessibility and quality
- Meet WCAG AA contrast where practical.
- Every informative image needs meaningful Japanese alt text.
- Preserve visible keyboard focus states.
- All controls must be keyboard usable.
- Respect `prefers-reduced-motion`.
- External links that open a new tab must use `rel="noopener noreferrer"`.
- Avoid layout shift by including image width/height or aspect-ratio.
- Check mobile widths at 375px, 768px, and desktop at 1440px.

## SEO
- Keep a unique title and accurate meta description.
- Keep canonical, Open Graph, Twitter Card, and Organization JSON-LD data valid.
- Update `sitemap.xml` when adding pages.
- Never expose private email addresses or personal data beyond explicitly approved public company information.

## Verification before completion
1. Inspect the existing repository and describe what will change.
2. Make a concise implementation plan before editing.
3. Validate HTML/CSS/JS for obvious syntax errors.
4. Check all local asset paths and external URLs.
5. Test the mobile menu with keyboard and Escape key.
6. Confirm there is no horizontal overflow at 375px.
7. Summarize modified files and any content requiring user confirmation.
8. Do not commit or push unless explicitly instructed.
