# Pinawe IT Helpdesk — Website

Coursework project for **IS229 – Web Design**, Bachelor of Business in Information Technology, 2026.

Built for Assessment 2 (semantic HTML5, multi-page structure) and extended for **Assessment 3** with a full external CSS system: colour variables, typography, Flexbox, CSS Grid, mobile-first media queries, responsive images, and visible focus states. No CSS framework was used.

## About this project

A five-page website for the internal/external IT Helpdesk of a fictional company, **Pinawe Software Co.** The site helps staff and registered clients understand what support is available, find self-service answers, and submit a support ticket or book an on-site visit.

**Target audience:** Pinawe Software Co. employees and registered software clients who need technical support.

**Primary user tasks the site supports:**
- Understand what the helpdesk covers and how quickly issues are handled.
- Find a self-service answer in the knowledge base before logging a ticket.
- Submit a detailed support ticket with the right priority and category.
- Book an on-site technician visit.
- Check current system status and recent announcements.

## Site map

| Page | File | Purpose |
|---|---|---|
| Home | index.html | Overview, ticket lifecycle, response-time targets, quick links |
| About | about.html | Team structure, mission, support tiers, AI use declaration |
| Services | services.html | Full list of supported service categories, scope, tutorial video |
| Knowledge Base | knowledge-base.html | Search, self-service guides, system status, announcements |
| Contact / Submit a Ticket | contact.html | Main support ticket form and on-site visit booking |

Navigation is consistent across all five pages via the header nav, and every page shares the same footer.

## Technology used

- **HTML5** — semantic elements throughout (header, nav, main, section, article, aside, figure/figcaption, footer).
- **CSS3** — one external stylesheet (css/style.css) with:
  - CSS custom properties (root variables) for colour, spacing and type
  - Flexbox for navigation, button groups, footer bottom row, radio/checkbox rows
  - CSS Grid for the hero, card layouts, process list, form grid, footer grid and the main-content-plus-sidebar layout
  - Mobile-first media queries at roughly 600px and 960px that restructure layout, not just resize it
  - Responsive images and video (max-width: 100%)
  - Visible focus states for keyboard navigation
- No Bootstrap, Tailwind or other CSS framework was used, per the assessment rules.
- **No JavaScript** is required for the site to function; all form validation uses native HTML5 attributes (required, type, pattern, minlength, maxlength, min, max).

## Project structure

pinawe-it/
index.html
about.html
services.html
knowledge-base.html
contact.html
css/
style.css
assets/
images/ (logo, hero illustration, team graphic, icons)
testing/ (mobile/tablet/desktop screenshots, testing notes)
README.md
AI_DECLARATION.md


## Published website

- **GitHub repository:** https://github.com/lydiapinawesapmangua-cell/is229_a2_lydia_SAPMANGUA_site
- **Live website:** https://lydiapinawesapmangua-cell.github.io/is229_a2_lydia_SAPMANGUA_site/

## Responsive testing evidence

See testing/TESTING.md for browser and viewport testing notes, and the mobile/tablet/desktop screenshots in the same folder.


## AI Declaration

I confirm that I directed and reviewed all AI assistance described above, This declaration is accurate to the best of my
knowledge at the time of submission.
