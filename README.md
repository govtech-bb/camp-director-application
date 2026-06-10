# Camp Director application — prototype

A clickable HTML prototype for the **National Summer Camp Programme 2026** service:
apply to be a Camp Director or Assistant Camp Director.

Built with the [GovBB design system](https://github.com/GovTechBB/design-system)
(`@govtech-bb/styles`, alpha).

## What it includes

- Combined start / entry page (what you need, cost, how long, what happens next)
- A 17-step form grouped by section, with working conditional logic and repeatable sections
- File uploads (photo, ID card, 2 reference letters, health certificate)
- Check your answers → agreement → confirmation with a reference number

## Running it

It's a single self-contained file. Either:

- Open `index.html` directly in a browser, or
- Serve the folder: `python -m http.server 8787` then visit <http://localhost:8787/>

The design system CSS and assets load from the published CDN, so no build step is needed.

## Status

Alpha prototype. Some content is placeholder pending confirmation from the
Ministry of Youth, Sports and Community Empowerment (application close date,
support email and phone number).
