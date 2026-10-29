# Bhavadharani S. — Developer Portfolio

A responsive, single-page portfolio built with semantic HTML, CSS, and vanilla JavaScript. It keeps the existing profile photograph and uses a dark charcoal, electric-lime, and subtle-violet visual system.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser.

For a local development server, open a terminal in this folder and run:
- Python: `python -m http.server 8000`
- Then visit `http://localhost:8000`

No build step or npm dependencies are required.

## Deploy
### Netlify
1. Sign in to Netlify and choose **Add new site** → **Deploy manually**.
2. Drag the extracted folder (containing `index.html` and `profile.jpg`) into the deploy area.
3. Open the generated URL and test it on mobile and desktop.

### Vercel
1. Put the files in a GitHub repository.
2. Import that repository into Vercel.
3. Choose the static/Other framework preset, leave the build command empty, and use `.` as the output directory if prompted.

## Before public submission
- Add your real resume PDF as `resume.pdf` in this folder. The page currently labels the resume as not included; it does not fabricate one.
- Add verified project-specific repository URLs and screenshots when available. Project cards currently link to the existing GitHub profile only where appropriate; no project-specific repository or demo links have been invented.
- Add a public email address only if you want it displayed. The old example email has been removed.
- Check that the GitHub and LinkedIn profile URLs are correct and public.
- Verify that all project status labels still reflect their actual status at submission time.

## Design and functionality
- Responsive desktop, tablet, and mobile layouts.
- Accessible hamburger menu with open/close state and auto-close after selecting a section.
- Active navigation indication, smooth anchor navigation, scroll reveal effects, and reduced-motion support.
- Custom project illustrations drawn as inline SVG, so no placeholder screenshots or external image assets are required.
- No frontend framework or build dependencies are required.
