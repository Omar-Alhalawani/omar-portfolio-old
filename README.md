# Engineering Portfolio — Previous Version

**Legacy static website • Bootstrap • HTML/CSS/JavaScript**

This repository contains a **previous iteration** of Omar Alhalawani's engineering portfolio. It presents experience and projects spanning ASIC verification, FPGA/RTL design, embedded systems, robotics, real-time computing, and Python data acquisition.

**Current portfolio:** [Live website](https://omar-alhalawani.github.io/omar-portfolio/) · [Current source repository](https://github.com/Omar-Alhalawani/omar-portfolio)

This older codebase is preserved as a snapshot of the site's earlier implementation and content architecture. The live link above points to the **current** site—not necessarily to this repository's contents.

## What this version showcases

- Multi-page engineering portfolio with home, about, resume, project directory, project detail, and contact pages
- Links to technical projects and professional profiles
- Responsive navigation and presentation
- Scroll effects and frontend components provided by Bootstrap and bundled libraries
- A resume PDF and local imagery under `assets/`

## Stack

| Layer | Technology |
| --- | --- |
| Markup and styling | HTML5, CSS3, Bootstrap 5 |
| Browser scripting | JavaScript |
| UI enhancements | Bootstrap Icons, AOS, Swiper, GLightbox, other bundled template assets |
| Hosting model | Static web pages, suitable for a conventional static file server |

This version was adapted from the **FolioOne** template by BootstrapMade; template credit and license information remain in the HTML source.

## Project structure

```text
index.html             # Landing page
about.html             # Personal/technical background
resume.html            # Experience and resume
projects.html          # Engineering project directory
project-details.html   # Detailed project content
contact.html           # Contact page
services.html          # Additional site page
assets/
  css/                 # Stylesheets
  js/                  # Frontend scripts
  img/                 # Site and project images
  resume/              # Resume document
  vendor/              # Bundled third-party frontend packages
```

## View locally

```bash
git clone https://github.com/Omar-Alhalawani/omar-portfolio-old.git
cd omar-portfolio-old
python -m http.server 8000
```

Open `http://localhost:8000` in a browser. Static navigation and layout can be explored locally; features that rely on external services may require additional configuration.

## Why retain this repository?

The prior version documents the portfolio's progression, including differences in information architecture, styling, responsiveness, and project presentation. It is **not the recommended starting point for the current site**.

## License and attribution

This is a personal project containing third-party template assets. Review the credits and licensing terms supplied by BootstrapMade and the included libraries before redistribution; the repository has no separate top-level license file.
