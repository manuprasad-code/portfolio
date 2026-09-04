# Manu Prasad — Mechanical Design Engineer

Single-page portfolio. Static site, no build step.

## Deploy on GitHub Pages
1. Push this folder's contents to the repo root (or to /docs).
2. Settings → Pages → Source: main branch, root (or /docs).
3. The site serves from index.html.

## Structure
- index.html — the portfolio (hero, about, process, selected work, experience, contact)
- project-*.html — one detail page per project
- support.js, image-slot.js — runtime scripts
- assets/ — images

## Replacing images
Overwrite the file at the same path and filename in assets/.

| Section | Path |
| --- | --- |
| Hero portrait | assets/hero-portrait.png |
| Footer portrait | assets/footer-portrait.png |
| Process 01 Sketch | assets/process-01-sketch.jpg |
| Process 02 CAD & simulation | assets/process-02-cad-simulation.png |
| Process 03 Prototype | assets/process-03-prototype.jpg |
| Process 04 Production | assets/process-04-production.jpg |
| Work 01 Hexacopter-6 | assets/work-01-hexacopter-6.png |
| Work 02 Underwater Inspection | assets/work-02-underwater-inspection.png |
| Work 03 Surveillance Hex | assets/work-03-surveillance-hex.jpg |
| Work 04 Gift Ball vending | assets/work-04-gift-ball-vending.jpg |
| Work 05 AI Toy | assets/work-05-ai-toy.jpg |
| Work 06 Fitknees | assets/work-06-fitknees.png |
| Tool logos | assets/logo-*.png / .jpg |

## Resume
Add your PDF as `assets/resume.pdf` — the footer button then downloads it for visitors.
