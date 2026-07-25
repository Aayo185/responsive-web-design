# Sparkle Academy — Responsive Web Design

A small responsive, multi-page static website built with HTML and CSS, created as a frontend practice project (semantic HTML, layout, and a shared stylesheet across pages).

## Pages

*   **`findex.html`** — Home page: intro, an embedded YouTube video, and a tech-stack overview table.
*   **`fregister.html`** — Course registration form (name, age, gender, email, course selection, resume upload).
*   **`event.html`** — Upcoming events listing.

All three pages share a single stylesheet, `style.css`, and a top navigation bar linking between them.

## Running It Locally

No build step or server is required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/Aayo185/responsive-web-design.git
    cd responsive-web-design
    ```
2.  Open `findex.html` directly in your browser (double-click it, or right-click → Open With → your browser).
3.  Use the nav bar at the top to move between Home, Register, and Events.

## Features

*   **Responsive layout:** Content reflows for smaller screens via a `max-width` container and a mobile breakpoint in `style.css`.
*   **Shared navigation:** All three pages link to each other through a consistent nav bar.
*   **Semantic HTML:** Headings, tables, and forms are structured with standard HTML elements.

## Known Limitations

*   The event page uses placeholder Lorem Ipsum text and a placeholder contact number/email — swap these for real content before using it live.
*   The registration form doesn't submit anywhere yet (no `action`/backend) — it's a static UI only.
*   No images are bundled with the project; the events page and headers are text/table-based rather than photo-based.

## Future Improvements

*   Wire the registration form up to a real backend or form service.
*   Add real event photography and academy branding assets.
*   Add active-page highlighting to the nav bar.

## License

This project does not currently include a license file. All rights reserved by the author unless a license is added.
