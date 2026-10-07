# Dr. Muhammad Shahid Iqbal Malik · MMX Lab

A modern, responsive academic website for GitHub Pages, including MMX Lab — Multilingual, Multimodal and Explainable AI.

## Publish on GitHub Pages

1. Extract this archive.
2. Upload the extracted contents to the root of your existing GitHub Pages repository. Keep every directory, including `assets/` and `lab/`.
3. Commit the changes using your existing GitHub Pages branch and folder settings.
4. The lab is available at `/lab/` for a username.github.io site, or `/REPOSITORY/lab/` for a project site. Relative navigation supports both.

No build step, npm installation, account, or backend is required. Do not upload only the ZIP file.

## Pages

- `index.html`: Dr. Malik’s homepage
- `lab/index.html`: MMX Lab, research areas, team, open-source work and joining
- `research/index.html`: research directions
- `publications/index.html`: existing publications
- `about/index.html`: academic biography
- `teaching/index.html`: teaching
- `service/index.html`: academic service
- `cv/index.html`: CV, with print support
- `contact/index.html`: contact
- `collaborate/index.html`: collaboration information

## Editing

- Edit `lab/index.html` to update the lab copy or research assistants.
- Research assistants currently listed: Aftab Nawaz, Rameesha Zia, Ahmed Ali Tariq. Initial avatars are intentional; add verified photos or biographies when available.
- Edit `assets/site.css` for shared colors, typography, spacing and responsive layout.
- Edit `assets/site.js` for navigation, research tabs and CV printing.
- All assets are included locally. Research and profile links point to the existing external destinations. There are no runtime font or JavaScript downloads.
- The language-and-vision illustration is an original SVG embedded in the lab page; it is conceptual rather than an architecture diagram.

## Preview locally

Run `python3 -m http.server 8000` from the extracted directory, then visit `http://localhost:8000`. You can also use VS Code Live Server.

## Accessibility and behavior

Keyboard-operated research tabs, visible focus states, mobile navigation, reduced-motion support, meaningful headings and a skip link are included. Scrolling uses the browser’s native smooth-scroll behavior. Academic content from the uploaded website is retained. Homepage presentation and shared navigation have been refreshed; the lab leadership and former group name have been updated.

Validation: local file links, page fragments, tab references, required lab copy, research assistant names and JavaScript syntax were checked. Browser visual testing was unavailable in the execution environment; verify desktop and mobile presentation after upload.
