# ai-strategies.org

Static two-page website for a frontier AI advisory initiative targeting the DACH region. Joint project of Matthias Samwald and Jason Hoelscher-Obermaier.

## Structure
- `index.html` — English landing page (brief framing + bios + contact)
- `dach.html` — German DACH page (primary content: context, services, bios, contact)
- `styles.css` — Shared stylesheet
- `favicon.svg` — SVG favicon (geometric "A" letterform)

## Tech
- Plain HTML + CSS, no JavaScript, no build step
- Designed for static hosting (GitHub Pages, Netlify, etc.)
- Remote: `git@github.com:matthias-samwald/ai-strategies-website.git`

## Design
- No header or footer — content only, with inline language switch
- Montserrat (headings, nav, CTA) + Noto Sans (body) via Google Fonts
- Navy (#253951) primary, light blue (#E8F2FC) accent
- 640px max-width content column
- Responsive: breakpoints at 768px and 480px, plus print styles
- Tone: understated, professional, serious experts
