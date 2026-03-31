# Finqua Landing Page

## Project Overview
Landing page for Finqua, a CRM designed exclusively for Personal Shoppers Inmobiliarios (PSIs) in Spain. Single conversion goal: get the PSI to request early access.

## Tech Stack
- Single-file HTML (`index.html`) — no build step needed
- Tailwind CSS 3.x via CDN (with inline config)
- Google Fonts: Newsreader (headlines), Work Sans (body), Space Grotesk (labels/data)
- Material Symbols Outlined (icons)
- No JavaScript framework

## Design System
See `template/DESIGN.md` for the full "Editorial Intelligence" specification.

Key rules:
- **0px border radius** on everything — sharp corners only
- **No drop shadows** — elevation via tonal surface layering
- **No stock photography** — UI screenshots or abstract visuals only
- **No horizontal dividers** — separation via background shifts and whitespace
- Colors: cream background (`#fbf9f4`), charcoal ink (`#171818`), ochre accent (`#745b21`)
- Typography: Newsreader (serif headlines), Work Sans (body), Space Grotesk (data/labels)

## Content Source
- `structure.md` — canonical copy and section structure for all 9 sections
- All content in Spanish. No English UI labels.
- CTA copy: "Solicitar acceso anticipado" (hero) / "Solicitar acceso como Cliente Fundador" (founding clients)

## Page Sections
1. **Hero** — headline + stat sidebar + CTA
2. **Problem** — 4 pain point cards
3. **Solution** — 3 pillars (encargos, propiedades, portal)
4. **Time Savings** — comparison table (6 activities + total row)
5. **AI Features** — 6 feature cards
6. **Workflow** — 7 phases of the PSI process
7. **Comparison** — 6-row table vs traditional CRMs
8. **Founding Clients** — benefits + conditions + CTA
9. **Footer** — tagline + legal links + contact

## Development
```bash
# Just open in browser — no build needed
open index.html
```
