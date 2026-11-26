# Riven Atlas

A static Warframe Riven reference site built from the user-provided guide.

## Included
- Searchable list of 419 weapon entries
- Selected-weapon profile with the guide's four primary preference fields
- Additional/alternate roll lines and source notes where present
- Searchable abbreviation glossary
- Copy roll summary and external Wiki search link
- Responsive layout; no backend, build tools, or third-party libraries

## Publish on GitHub Pages
1. Create a new GitHub repository (for example `riven-atlas`).
2. Upload `index.html` and `data.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will appear in that Pages section.

## Run locally
Open `index.html` in a browser. Keep `data.js` in the same folder.

## Data notes
The site preserves the source guide's recommendations and notes as extracted into the workbook's Weapon Data and Abbreviations sheets. The labels "Preference 1–4" are intentionally neutral; the source itself uses compact positional columns and some weapons have alternate rows. This site is a static snapshot, not a live Warframe database.

## Full stat names
Stat abbreviations in the source recommendations are expanded to full names, with the original abbreviation retained in parentheses (for example, `Multishot (MS)`). The source glossary uses `EFF` for both Ammo Efficiency and Heavy Attack Efficiency; the website identifies this ambiguity instead of silently choosing one.
