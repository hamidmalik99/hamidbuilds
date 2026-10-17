# hamidbuilds.dev

Static portfolio site for Hamid Ali Asad (GitHub Pages).

- `index.html` — homepage (agencies + small businesses)
- `work.html` — full portfolio, filterable
- `assets/projects.js` — project list. Add a site as `{"n": name, "u": url, "c": category, "g": filter group, "r": region}`
- `assets/site.js` — screenshots, contact form, testimonials

Project screenshots are captured live from each site by WordPress.com mShots and cached after the first visit.

Testimonials live in `assets/site.js` and stay hidden until a quote is marked `approved: true` (only after the client has OK'd the wording).
