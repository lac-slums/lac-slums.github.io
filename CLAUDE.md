# Project: LAC Slums GitHub Pages Website

**Parent Project:** Slums over time and space (slums-over-time)
**URL:** https://lac-slums.github.io
**Repository:** https://github.com/lac-slums/lac-slums.github.io

---

## What We're Doing

Building and maintaining the public-facing website for the LAC Slums Comprehensive Dataset. The site showcases the 11-country slum panel data and household data, with download links for researchers.

---

## Current Open Tasks

- [ ] Add working paper link (hero status badge, `index.html` line 35, replace `href="#"`)
- [ ] Add CSV download link (`index.html` ~line 195)
- [ ] Add GeoPackage download link (`index.html` ~line 195)
- [ ] Add Chile .dta download link (`index.html` ~line 195)
- [ ] Fill in professor/researcher names in Acknowledgments section

---

## File Structure

```
.
├── index.html       — main website (edit directly)
├── style.css        — styling (edit directly)
└── sample_countries.pdf
```

---

## Workflow

1. Edit `index.html` or `style.css` in VSCode
2. Test locally (optional: `python -m http.server 8000` and view at `localhost:8000`)
3. Commit: Source Control panel or `git commit -m "message"`
4. Push: `git push` or Source Control panel
5. Site goes live in ~60 seconds at `lac-slums.github.io`

---

## Links Needed

When ready, provide:
- Working paper URL
- CSV file URL (from Where?)
- GeoPackage file URL (from Where?)
- Chile .dta file URL (from Where?)
- Researcher/professor names for Acknowledgments
