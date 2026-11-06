# Hope Protestant Church Valencia · Iglesia Protestante La Esperanza

Bilingual (English / Spanish) landing page for the IEE congregation in Valencia —
**Hope Protestant Church Valencia / Iglesia Protestante La Esperanza / Església Protestant de l'Esperança**.

## What's here
- `index.html` — the complete landing page. Fully self-contained: all CSS, JavaScript,
  and images (the church seal and the IEE logo) are embedded, so there are no external
  file dependencies.
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll processing).

## Languages
The page is fully bilingual with an EN/ES toggle. On load it picks a default language
from the domain the visitor used:

| Domain | Opens in |
| --- | --- |
| `hopechurchvalencia.es` | English |
| `laesperanzavalencia.es` | Spanish |

A visitor's manual toggle is remembered (per domain) and overrides the default.
A Google Translate bar handles additional languages.

## Hosting the two domains — important
For the language-by-domain behaviour to work, **both domains must serve this same site.
Do NOT 301-redirect one domain to the other.** A redirect erases which domain the visitor
typed, so they would always get the destination domain's language.

`index.html` names `https://hopechurchvalencia.es/` as the SEO canonical, so search
engines treat that as the primary address.

## Status
A single landing page for now; further pages to be added later.
