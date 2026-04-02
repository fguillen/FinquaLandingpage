# Finqua Landing Page — SEO & AIO Improvements

Based on the SEO & AIO audit (April 2, 2026).

## Quick Wins

| Status | Title | Difficulty | Comment |
|--------|-------|------------|---------|
| [ ] | Move site to `finqua.app` custom domain | Low | GitHub Pages supports custom domains natively. Everything else builds on a credible domain. |
| [x] | Add `<meta name="description">` tag | Very low | Already existed. |
| [x] | Add `<link rel="canonical">` tag | Very low | Already existed. |
| [x] | Add JSON-LD `SoftwareApplication` schema | Low | Helps AI and search engines understand what the page is about. |
| [x] | Add JSON-LD `Organization` schema | Low | Name, URL, contactPoint. |
| [x] | Add JSON-LD `FAQPage` schema | Low | Single most impactful AIO action — pair with FAQ section. |
| [x] | Create `/llms.txt` file | Very low | Plain-text file telling AI crawlers what the site is, key features, and how to cite it. |
| [x] | Add entity-definition paragraph in first 100 words | Very low | Clear, citable sentence defining what Finqua is — AI systems need this to surface the page. |

## On-Page SEO

| Status | Title | Difficulty | Comment |
|--------|-------|------------|---------|
| [ ] | Rewrite H1 to include primary keyword | Low | Current H1 has no target keywords. Should contain "CRM" + "Personal Shopper Inmobiliario". |
| [ ] | Spell out "Personal Shopper Inmobiliario" 3-4 times across page | Low | Currently uses "PSI" abbreviation too often; search engines need the full phrase. |
| [ ] | Add semantic keyword variants throughout copy | Low | "software PSI", "herramienta para agente del comprador", "gestión de encargos inmobiliarios", "CRM para representante del comprador". |
| [ ] | Add FAQ section (8-10 questions) | Medium | Targets long-tail keywords + featured snippets + AI Overviews. Questions like "¿Qué es un CRM para PSI?", "¿En qué se diferencia Finqua?", etc. |
| [x] | Fix typos: "taréas" → "tareas", "accumulado" → "acumulado" | Very low | Doesn't hurt SEO but hurts credibility. |
| [ ] | Add `sitemap.xml` | Very low | Almost certainly missing on current GitHub Pages setup. |
| [ ] | Add customized `robots.txt` | Very low | GitHub Pages uses its own by default. |

## Trust & Credibility

| Status | Title | Difficulty | Comment |
|--------|-------|------------|---------|
| [ ] | Add real social proof / testimonials | Medium | Current quote reads like an internal calculation, not a real testimonial. |
| [ ] | Add founder/team section | Medium | E-E-A-T signal — who's behind Finqua? |
| [ ] | Show actual pricing in "Clientes Fundadores" section | Medium | Nav links to `#precios` but no pricing shown. Missed keyword opportunity for "precio CRM inmobiliario". |

## Content Strategy (Medium-term)

| Status | Title | Difficulty | Comment |
|--------|-------|------------|---------|
| [ ] | Blog post: "Guía completa del flujo de trabajo del PSI" | High | Targets "proceso personal shopper inmobiliario". Positions Finqua as authority on PSI methodology. |
| [ ] | Blog post: "CRM inmobiliario vs. Notion para PSIs" | High | Attacks the PropertyBuyers/Notion association directly. |
| [ ] | Blog post: "Cómo automatizar la due diligence inmobiliaria" | High | Targets "due diligence compra vivienda". |
| [ ] | Blog post: "Cuánto cuesta un Personal Shopper Inmobiliario en 2026" | High | High-volume informational query attracting both PSIs and their potential clients. |
| [ ] | Blog post: "Informe de preselección inmobiliaria: plantilla y buenas prácticas" | High | Practical content PSIs would bookmark and share. |
| [ ] | Get listed on AEPSI or PSI-related directories | Medium | Builds domain authority and backlinks. |
