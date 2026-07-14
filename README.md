# Mapping Financial Stability Risk in the Australian Financial System

An interactive, single-file map of where risk concentrates in the Australian financial system, how stress could travel through it in a crisis, and — just as importantly — what regulators can and cannot currently see.

**22 sectors and markets · 39 documented linkages · 4 step-through stress scenarios · a "what we can and can't see" data-visibility overlay**

Every node and connection opens an evidence panel with key figures, a data-visibility rating, an explanation of how stress travels through that channel, and links to the underlying primary sources.

## How to explore

The map is a layered flow diagram: offshore vectors at the top, asset owners and lenders in the middle tiers, markets and infrastructure below them, and the real economy at the bottom. Arrowheads show the primary direction stress flows.

Three ways in: step through the **stress scenarios** in the top bar (global risk-off, private credit defaults, cyber/operational, China/trade), toggle **"What we can & can't see"** to recolour everything by how well it is actually measured, or simply **click any line** — start with superannuation → banks, the single most important domestic linkage the RBA identifies.

## Hosting on GitHub Pages

1. Create a new repository and upload the contents of this folder (`index.html`, `README.md`, `.nojekyll`).
2. In the repository: **Settings → Pages → Build and deployment**, set Source to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
3. The map will be live at `https://<your-username>.github.io/<repository-name>/` within a minute or two.

No build step, no dependencies, no server-side code — it is one self-contained HTML file.

## Evidence base

The map is a stylised synthesis of public assessments as at the RBA *Financial Stability Review* of March 2026. Principal sources:

- RBA *Financial Stability Review*, March 2026 and October 2025 (including the Box on interconnections between banks and non-bank financial institutions, and Focus Topic 4.1 on how overseas shocks affect financial stability in Australia)
- ASIC Report 814, *Private Credit in Australia* (September 2025) and Report 820 progress update (November 2025)
- APRA's first system risk stress test (Phase 1 findings as reported in the March 2026 FSR)
- Financial Stability Board, *Vulnerabilities in Private Credit* (May 2026)
- Council of Financial Regulators publications and RBA speeches as cited in the in-map source lists

Full citations with links appear in the panel for each node and connection.

## Caveats

This is an analytical visualisation, not advice, and not an official publication of any regulator. Figures are approximate, drawn from the cited public sources, and dated — several (notably the private credit exposure estimates) are explicitly flagged in-map as estimates rather than supervised facts. RBA material is reproduced in summary form with attribution; see the [RBA copyright notice](https://www.rba.gov.au/copyright/) for terms applying to that material.
