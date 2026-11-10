# DE-EXTINCTION LAB — The Genome Vault

An interactive, static educational website built from the team's **Genome Project Information** and **Complete Research and Experience Blueprint** documents.

## Included
- Cinematic homepage and substantial introductory content
- Scientific Mode with seven research archives, four detailed species records, conservation case studies and source links
- Explorer Mode with four independent expeditions, evidence boards and locally saved completion badges
- Eight playable mini-games: specimen identification, word clues, DNA complementary pairing, tic-tac-toe, Snake, specimen shuffle, evidence-based proxy studio and memory matching
- Responsive layout, keyboard-friendly navigation, reduced-motion control and semantic landmarks

## Run locally
Open `index.html` in a modern browser. The website has no server-side dependencies. For more consistent testing, use VS Code Live Server or run `python -m http.server 8000` inside the folder and visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a **public** GitHub repository named `de-extinction-lab`.
2. Upload `index.html`, `styles.css`, `app.js`, `content.js` and `.nojekyll` to the repository root (README optional).
3. Open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Wait for GitHub Pages to finish deployment. The URL will usually be `https://YOUR-USERNAME.github.io/de-extinction-lab/`.
5. Test the live URL on desktop and mobile, and click through every research link and game.

## Editorial notes
- The fictional archive setting and arcade games are explicitly educational storytelling, not experimental biotechnology.
- Research paragraphs are adapted from the team's supplied blueprint. Sources have not all been independently checked for complete APA metadata; verify publication details and external links before academic submission.
- Some games intentionally model simplified concepts (DNA base pairing, evidence categorisation). They do not simulate full genome assembly or gene editing.
- Decorative graphics are generated in CSS; species emoji are platform-dependent illustrations, not scientifically accurate reconstructions.
- Progress is stored in the browser's localStorage, not synchronised across devices.
- Google Fonts are requested over the internet; fallback fonts are provided if unavailable.

## Recommended final QA
Check scientific claims and reference metadata, review image/illustration attribution, validate mobile touch controls, keyboard accessibility and all eight games. GitHub Pages must be enabled by the repository owner; creating these files does not automatically publish a live site.


## Bright Museum Update (November 2026)
- Added `bright-theme.css` for a lighter navy/teal/lavender palette.
- Added expanded method exhibits, key-point summaries, scientific explanations and original-research expanders.
- Added external Wikipedia article thumbnail lookups to relevant exhibit/species images; these require an internet connection, may vary, and are **not** a vetted/licensed image library. Review each image and its Wikimedia Commons license before academic publication.
- Added exact class module and team credits provided by the user.
- Existing playable activities and four original expedition routes are retained in this update. Ten animals and three difficulty levels per game are **not yet implemented**; they remain planned for the subsequent Explorer rebuild.
- Upload all files, including `bright-theme.css`, `research-exhibits.js`, and `v2-experience.js`, to the repository root.


## V4 focused repair (2026-11-10)
- Restored Scientific Mode sidebar initialization and default Archive 01 rendering. This was accidentally removed in V3.
- Preserved the V3 dark homepage/research and bright Explorer Mode.
- Kept the detailed research exhibits, references, method gallery, credits and V3 checkers replacement.
- Rewrote only the four context introductions to approximately 100 words each, retaining four key points per section.
- Deploy all files at repository root (including research-exhibits.js and context-content.js).


## V5 updates
- Species records: specimen image above a compact name, description and Explore prompt.
- Case studies and ethics: interactive image-backed reveal cards.
- Explorer expedition cards: responsive image dimensions and no horizontal overflow.
- Introductory context: approximately 50 words per paragraph, followed by key points.
- All scientific archive panels and research methods retained.
- Image thumbnails use Wikipedia and may not always load; review rights and attribution before final submission.


## V6 homepage credits
The first-screen hero now prominently displays the exact module and all six creator names supplied by the team. `v6-credits.css` must be uploaded alongside the other files. All previous V5 research and game files are retained.
