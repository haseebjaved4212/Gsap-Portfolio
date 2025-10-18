# Portfolio GSAP Template

A minimal, animated portfolio template built with GSAP and Locomotive Scroll. This repository is a starting template, feel free to customize text, assets, styles and animations to fit your needs.

## Live preview
Open [index.html](index.html) in a browser (or serve the folder with a static server) to view the template.

## Features
- Hero section with entrance animations driven by GSAP.
- Custom cursor / follower (#minicircle).
- Project list with hover preview images.
- Smooth scrolling via Locomotive Scroll.
- Simple, easy-to-edit structure and styles.

## Files
- [index.html](index.html) — main HTML file.
- [script.js](script.js) — animation and interaction logic (see functions below).
- [style.css](style.css) — main styles and layout.
- [loco.css](loco.css) — Locomotive Scroll helpers.
- [assets/](assets/) — images used in the template.

## Important functions (scripts)
The interactive behavior is implemented in [script.js](script.js). Key functions you may edit:
- [`firstPageAnim`](script.js) — hero entrance animation and timeline.
- [`circleChaptaKaro`](script.js) — sets up cursor scaling logic on mousemove.
- [`circleMouseFollower`](script.js) — moves and scales the custom cursor image on hover/move.

Edit those functions to change timing, easing, or animation sequences.

## Dependencies
External libraries are loaded via CDN in [index.html](index.html):
- Locomotive Scroll: [locomotive Documentation]( https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.min.js)
- GSAP: [GSAP Documentation](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.5/gsap.min.js)

## How to run locally
1. Clone or copy the project folder.
2. Open [index.html](index.html) in your browser.
   - Or, serve the folder (recommended for better asset/path behavior):
     - Python: `python -m http.server 8000`
     - Node (http-server): `npx http-server .`
3. Visit http://localhost:8000 (or the port you chose).

## How to customize (recommended)
- Replace placeholder text (e.g., "John Doe") in [index.html](index.html).
- Replace images in [assets/](assets/) and update src paths in [index.html](index.html).
- Update fonts by replacing @font-face sources in [style.css](style.css).
- Tweak timings/easings in the functions (`firstPageAnim`, `circleChaptaKaro`, `circleMouseFollower`) in [script.js](script.js).
- Add or remove project entries inside the `#second` section of [index.html](index.html).

## Notes & tips
- The project is intended as a template — modify it to match your branding, routes, and portfolio items.
- Keep accessibility in mind: add alt text to images, proper link labels, and keyboard navigation.
- If you use Locomotive Scroll features beyond basic smooth scrolling, review [loco.css](loco.css) and initialize additional options in [script.js](script.js).

## License
This project is a template. Use and adapt freely; include attribution if you publish derivative works.

---

Template files in this workspace:
- [index.html](index.html)  
- [script.js](script.js) — contains [`firstPageAnim`](script.js), [`circleChaptaKaro`](script.js), [`circleMouseFollower`](script.js)  
- [style.css](style.css)  
- [loco.css](loco.css)  
- [assets/](assets/)

--- 
<div align="center">
  Created with ❤️ by Haseeb Javed
</div>