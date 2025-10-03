# AI Tech Co. - Website Project

Overview
- A complete, modern AI technology company website generated for a tech category prompt.
- Built with Tailwind CSS (via CDN) and semantic HTML.
- Includes 4 pages: Home (index.html), About (about.html), Solutions (solutions.html), and Contact (contact.html).
- All pages follow responsive design best practices and accessible markup where feasible.
- Phase 2 output for this session is the full set of pages and a README with guidance.

Content & Design Notes
- Theme: Modern/Minimalist with a professional color palette (indigo/navy accents).
- Typography: Uses Inter for body and Montserrat for headings (via font-[Inter] and font-[Montserrat] utility classes).
- Hero sections use a background image placeholder placeholder syntax: https://images.unsplash.com/photo-1757325331955-9ba8182dc44e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw1fHwuLi58ZW58MHwwfHx8MTc1OTQyNzU1OXww&ixlib=rb-4.1.0&q=80&w=1080 per the placeholder system described in the spec.
- All interactive elements include transitions (Tailwind utility classes) for a polished user experience.

File List
- index.html: Home page with hero, features, and CTAs.
- about.html: Company story, team, and values.
- solutions.html: Overview and cards for AI solutions.
- contact.html: Contact form and map placeholder.
- README.md: This file.

How to Use / Extend
- To add more pages, copy a page structure (e.g., copy index.html), update content, and extend the navigation in all pages.
- For adding new sections, follow the existing pattern (cards/sections using Tailwind utilities).
- Ensure internal linking remains consistent (your navigation links must point to existing pages).

Notes on Accessibility & SEO
- All images (where used) should include descriptive alt attributes.
- Use semantic tags (header, nav, main, section, footer).
- Each page includes a meaningful title and a concise meta description.

That's it! You can deploy these pages as a static site or integrate them into a larger framework as needed.