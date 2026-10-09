# INFR3120 Assignment 1 — Personal Portfolio

A four-page personal portfolio built with HTML5 and CSS3 for INFR3120 Web and Scripting Programming.

## Pages
- `index.html` — Home page and navigation
- `about.html` — Personal introduction, own photo, and HTML5 video
- `projects.html` — Five project/learning entries to customize with genuine coursework
- `contact.html` — Contact form with native HTML validation

## Folder structure
```text
INFR3120-Portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── README.md
├── css/
│   ├── style.css
│   ├── mobile.css
│   ├── tablet.css
│   └── laptop.css
├── assets/
│   ├── profile-photo-placeholder.svg
│   └── video-poster.svg
└── media/
    └── intro.mp4  (add your own 45–60 second video)
```

## Responsive viewports
- **Mobile:** up to 600px, in `css/mobile.css`. A single-column layout and compact navigation help readability on narrow screens.
- **Tablet:** 601px–1024px, in `css/tablet.css`. Inline-block two-column layouts make better use of medium-width screens.
- **Laptop/desktop:** 1025px and wider, in `css/laptop.css`. Wider columns and additional decorative elements use available space.
- `css/style.css` contains shared styles and components.

The assignment says not to use Flexbox; this project uses normal document flow, inline-block, percentage widths, and media-query styles instead. Do not add `display: flex` or `display: inline-flex`.

## Colour scheme
A custom dark technology palette inspired by Adobe Color:
- Charcoal background: `#0b0f17`
- Panel: `#111927`
- Electric blue: `#3b82f6`
- Cyan accent: `#22d3ee`
- Main text: `#edf3ff`
- Muted text: `#a5b2c7`

The colours are defined as CSS custom properties in `css/style.css` and used consistently across navigation, cards, links, and buttons.

## Gradients
- A standard linear gradient is used on primary buttons, the brand mark, and the decorative orbit core.
- An angled linear gradient is used on the text `.gradient-text` and the muted section background.
- These styles are defined in `css/style.css`.

## Before you submit
1. Replace `YOUR_EMAIL@example.com` in all four HTML files with an email address you want to publish.
2. Replace `assets/profile-photo-placeholder.svg` with your own photo. Keep the filename `profile-photo-placeholder.svg` only if you retain the SVG; otherwise update the `<img src>` in `about.html` to the filename of your own image.
3. Record a 45–60 second introductory video and save it as `media/intro.mp4`. Replace `assets/video-poster.svg` with your own poster image or update its path in `about.html`.
4. Edit the five project entries so they describe actual work you completed. Do not claim projects you did not do.
5. Test the form. It uses browser validation and a `mailto:` action, so it opens the visitor's email application rather than sending messages through a server.
6. Test every page and navigation link on mobile, tablet, and desktop widths.
7. Run the HTML, CSS, link, spelling, and WAVE accessibility checks listed below and fix any errors you find.

## Validation and accessibility
- HTML: https://validator.w3.org/
- CSS: https://jigsaw.w3.org/css-validator/
- Link checker: https://validator.w3.org/checklink
- Accessibility: https://wave.webaim.org/

Validate all four HTML files and all CSS files. Review the output and fix issues before submission; do not claim validation has passed until you have run the checks.

## GitHub and deployment
1. Create/sign in to a GitHub account.
2. Create a **public** repository named `infr3120-portfolio`.
3. Upload all project files and folders, preserving the folder structure. Commit the first version.
4. Make additional commits after meaningful edits (for example, content, responsive styling, and final fixes). Use accurate messages that describe the change.
5. In the repository, open **Settings → Pages**. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. The live URL normally looks like `https://YOUR-USERNAME.github.io/infr3120-portfolio/`. Use the actual URL shown by GitHub.
7. Open the live URL and check all four pages, images, video, navigation, and form.
8. Keep the repository public.

## Suggested video outline (15–20 minutes)
- 0:00–1:30 — Introduce yourself and show the live website.
- 1:30–4:00 — Explain the folder structure and four separate HTML files.
- 4:00–7:00 — Explain semantic elements, navigation, page content, and footer.
- 7:00–10:00 — Explain CSS variables, typography, colours, gradients, and cards.
- 10:00–12:30 — Explain the separate mobile, tablet, and laptop CSS files and why Flexbox is not used.
- 12:30–14:00 — Explain the video element, poster, and contact form validation.
- 14:00–17:00 — Demonstrate validation/testing and Git commits.
- 17:00–19:00 — Show GitHub Pages deployment and the public repository.
- Keep your webcam on for the entire recording. Speak in your own words and be ready to explain the code.

## External code/source disclosure
This starter project was generated with assistance from ChatGPT. Review and understand every section, adapt the code yourself, and follow your instructor's policy for acknowledging AI assistance. No third-party template or external code library is intentionally included. If you add external code or assets, cite the source and author here as required by the assignment.
