# infinitymep.ge

Site for **Infinity MEP** — independent MEP (mechanical / electrical / plumbing) engineering & construction consulting in Tbilisi, Georgia.

Served via **GitHub Pages** on the custom domain **infinitymep.ge** (no build step).

## Current landing page — 3D flagship
`index.html` is a premium landing page with an interactive **3D building hero** (Three.js / WebGL) plus
professional content (services, contact), bilingual EN / ქართული.
- **Hero**: orbit the glass tower (drag), zoom (wheel), **explode** the floors (slider) to reveal the
  live **MEP systems** running inside — water / HVAC / power, each with animated flow; toggle systems on/off.
  Premium lighting (environment reflections, soft shadows, bloom on the glowing systems).
- **Services** + **Contact** sections, refined editorial typography (Fraunces / Archivo / IBM Plex Mono).
- Source also at `concepts/flagship.html`.

## Other versions (kept for reference)
- `landing-cad.html` — text-free interactive AutoCAD/ArchiCAD-style site plan.
- `landing-classic.html` — earlier bilingual text landing page.
- `concepts/` — alternative interactive concepts + gallery (`concepts/index.html`).

## Local preview
Open `index.html` in a browser, or `python -m http.server 8000`.

## Deployment
Push to `main`; GitHub Pages serves automatically. Custom domain pinned by `CNAME`.
DNS import file for Cloudflare: `dns/infinitymep.ge.zone`.
