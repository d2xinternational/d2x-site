# D2X International — site vitrine

Refonte moderne du site [d2x.fr](https://d2x.fr). Cabinet de conseil en programmation et AMO pour maîtres d'ouvrage publics, fondé en 1983.

Site statique, zéro build, déployable tel quel sur GitHub Pages, Netlify, Cloudflare Pages ou OVH.

## Structure

- `index.html` — Accueil
- `a-propos.html` — À propos (histoire, valeurs, chronologie)
- `missions.html` — Nos missions (Stratégie, Faisabilité, AMO Suivi, AMO Exploitation)
- `references.html` — Références (4 catégories)
- `equipe.html` — Notre équipe (14 membres)
- `contact.html` — Contact
- `styles.css` — Design system partagé

## Design

- Direction : corporate moderne (sans-serif, bleu)
- Typographies : Space Grotesk (titres) + Inter (corps) + Instrument Serif (accents) — Google Fonts CDN
- Palette : bleu `#1e4fd9`, encre `#0a1628`, accent teal `#00b8a9`
- 100 % responsive, pas de framework, pas de JS (hors menu burger et form stub)

## Dev local

```bash
cd ~/Desktop/d2x-site
python3 -m http.server 8000
# puis http://127.0.0.1:8000
```
