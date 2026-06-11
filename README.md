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

Alpha prototype, owned by the Division of Youth Affairs, Division of Youth and
Culture, Prime Minister's Office. Some content is still placeholder pending
confirmation (application close date and support phone number).
