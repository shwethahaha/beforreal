# Be For Real - Agency Website

A multi-page, fully responsive portfolio website built for "Be For Real," a full-service creative agency. The design follows a bold "Desi Maximalism" and Brutalist aesthetic, featuring high-contrast colors, harsh shadows, and heavy typography.

## Tech Stack

* **HTML5:** Semantic markup for all pages.
* **Tailwind CSS:** Styling handled entirely via Tailwind CDN for rapid, utility-first design.
* **JavaScript:** Vanilla JS used strictly for Intersection Observer scroll animations (fade-ins).
* **Fonts:** 'Inter' from Google Fonts.

## File Structure

The website consists of 6 standalone HTML pages:

1.  `index.html`: The high-impact landing page and summary.
2.  `about.html`: Agency story, philosophy, and target audience.
3.  `services.html`: Interactive, brutalist list of all 13 agency services.
4.  `process.html`: The 5-step "0 to 100" methodology.
5.  `why-us.html`: The agency manifesto and client testimonials/stats.
6.  `contact.html`: Direct contact information and project inquiry form.

## Color Palette (Desi Maximalism)

Configured within the Tailwind script in the `<head>` of each file:

* **Primary:** Persian Indigo (`#2D1C7F`)
* **Secondary/Accent:** Wisteria (`#B0A9E5`)
* **Dark/Text:** Ink Black (`#0D0E20`)
* **Background:** Milk/Linen (`#FFF3E6`)

## Key Features

* **Sticky Frosted Navigation:** Backdrop blur applied to the top header for a premium glass effect.
* **Scroll Animations:** Elements fade and slide up into view using a custom Intersection Observer script.
* **Infinite Marquee:** CSS-only continuously scrolling text banner.
* **Brutalist Hover States:** Hard, unblurred drop-shadows and structural scaling on hover interactions.

## Setup & Usage

No build process, Node modules, or compilation is required. 

1. Ensure all `.html` files and your logo (`newlogo.png`) are in the same root folder.
2. Open `index.html` in any modern web browser to view the site locally. 
3. For the best development experience, open the folder in VS Code and use the "Live Server" extension.
