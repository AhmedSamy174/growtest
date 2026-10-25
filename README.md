# GrowTest — growtest.net

Grow-gear reviews written on published numbers (PPF, µmol/J, VWC accuracy, light transmission), in English and Arabic.

- Owner & operator: Eng. Osama Samy (Aswan, Egypt)
- Contributing reviewer: Ahmed Samy (plant physiologist; volunteer)
- Hosting: Cloudflare Workers/Pages, deployed automatically from the `main` branch.

## Structure
- `public/index.html` — the whole site (all pages + both languages, hash-routed).
- `content/` — research notes and the article queue used by the scheduled update task.

## Editing
Change `public/index.html`, open a pull request, merge → live within a minute.
