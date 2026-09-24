# Pinawe IT Helpdesk — Website

Coursework project for **IS229 – Web Design, Assessment 3** (Bachelor of Business in Information Technology, 2026). Originally built for Assessment 2 and extended here into a fully responsive, styled site.

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
| Home | `index.html` | Overview, ticket lifecycle, response-time targets, quick links |
| About | `about.html` | Team structure, mission, support tiers, AI use declaration |
| Services | `services.html` | Full list of supported service categories, scope, tutorial video |
| Knowledge Base | `knowledge-base.html` | Search, self-service guides, system status, announcements |
| Contact / Submit a Ticket | `contact.html` | Main support ticket form and on-site visit booking |

Navigation is consistent across all five pages via the header `<nav>`, and every page shares the same footer.

## Technology used

- **HTML5** — semantic elements throughout (`header`, `nav`, `main`, `section`, `article`, `aside`, `figure`/`figcaption`, `footer`).
- **CSS3** — one external stylesheet (`css/style.css`) for readability and spacing only. No CSS framework (Bootstrap/Tailwind) is used, per the assessment rules.
- **No JavaScript** is required for the site to function; all form validation is done with native HTML5 attributes (`required`, `type`, `pattern`, `minlength`, `maxlength`, `min`, `max`).

## Project structure

```
pinawe-it-helpdesk/
├── index.html
├── about.html
├── services.html
├── knowledge-base.html
├── contact.html
├── css/
│   └── style.css
├── assets/
│   ├── images/        # SVG logo, illustrations and icons
│   └── media/          # video walkthrough + captions
├── VALIDATION.md
└── README.md
```

Video walkthrough source: https://www.youtube.com/watch?v=RX5diMwVZqA&t=2s
Published Websites

Github Repository: https://github.com/lydiapinawesapmangua-cell/is229_a2_lydia_SAPMANGUA.git
Live Websites:  https://lydiapinawesapmangua-cell.github.io/is229_a2_lydia_SAPMANGUA/

## AI Declaration

This project was scaffolded with AI assistance (see the AI Use Declaration on the About page — `about.html#ai-declaration`). Before submitting, you should:

- Update the AI Use Declaration table on `about.html` so it reflects exactly what you used AI for on **this** assessment (A3 CSS/styling work), not just the A2 scaffolding.
- Confirm your declaration matches your unit's academic integrity policy.
- Update the Published Websites links above once the A3 version is live.
- Make sure your Git history shows real, incremental commits rather than one large final commit.
