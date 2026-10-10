
George Aduamah — Personal Portfolio

A multi-page personal portfolio built with HTML5 and CSS3 for INFR3120. It introduces me, presents selected projects and learning activities, and provides contact information.
Website pages

    Home (index.html) — Introduction, areas of interest, and links to the other pages.
    About Me (about.html) — Background and interests, portrait, and short introduction video.
    Projects (projects.html) — Cards describing selected projects or learning activities.
    Contact (contact.html) — Contact details and a form using native browser validation.

Project structure
.
├── index.html

├── about.html

├── projects.html

├── contact.html

├── README.md

├── assets/

│   ├── george.PNG

│   ├── profile-photo-placeholder.svg

│   └── video-poster.svg

├── css/

│   ├── style.css

│   ├── mobile.css

│   ├── tablet.css

│   └── laptop.css

└── media/

    └── george.mp4
Technologies

    HTML5 semantic elements and document structure
    CSS3 for colours, typography, layout, gradients, and responsive adjustments
    Native HTML form validation
    HTML video element with browser controls
    Git and GitHub for source control
    GitHub Pages for static hosting

Responsive breakpoints

The website uses a shared stylesheet and three screen-width-specific stylesheets.
Stylesheet	Media condition	Intended viewport
css/style.css	Loaded on all screen sizes	Shared base design
css/mobile.css	max-width: 600px	Mobile: 600 px wide or less
css/tablet.css	min-width: 601px and max-width: 1024px	Tablet: 601–1024 px
css/laptop.css	min-width: 1025px	Laptop/desktop: 1025 px and above

Each HTML page includes a viewport meta tag to support responsive display on mobile, tablet, and desktop screens.
Colour scheme and visual design

The visual design uses a dark charcoal background, bright blue accents, light primary text, and muted secondary text. This creates a technology-focused appearance and helps links, buttons, and headings stand out.

The design uses linear gradients, including an angled linear gradient, to add visual emphasis. Reusable classes such as container, eyebrow, button, and site-footer help maintain a consistent appearance across the pages.
Images and video

    The portrait is referenced in about.html as assets/george.PNG.
    The video poster is assets/video-poster.svg.
    The introduction video is referenced as media/george.mp4 and uses the browser's HTML video controls.

Contact form

The contact form uses native browser validation, including required fields, an email input type, length limits, and a phone-number pattern. Its mailto: action opens the visitor's configured email application; it is not a server-backed form handler and does not store submissions.
Accessibility

The pages use semantic HTML, a skip-to-content link, navigation labels, an aria-current marker for the active page, alternative text for the portrait, and explicit labels for form fields.
Deployment with GitHub Pages

    Push the HTML, CSS, image, video, and README files to a public GitHub repository.
    Open Settings → Pages in the repository.
    Select deployment from a branch.
    Choose the main branch and repository root (/) when the HTML files are in the repository root.
    Save the settings and open the published GitHub Pages URL.

Version control

Git and GitHub are used to manage the source code and record project changes through commits.
Viewport and colour notes

    Mobile: 600 px wide or less.
    Tablet: 601–1024 px wide.
    Laptop/desktop: 1025 px wide or more.
    Colour scheme: dark charcoal, bright blue accents, light primary text, and muted secondary text.
    Gradient use: linear gradients and an angled linear gradient are part of the visual design.
