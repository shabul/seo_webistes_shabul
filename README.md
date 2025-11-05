# Shabul Portfolio Site

A single-page portfolio built from the BootstrapMade DevFolio template and customized for Shabul Hussain Abdul. The site highlights experience as an Amazon data scientist, features galleries from recent events, embeds long-form Google I/O talks, and showcases vertical YouTube Shorts.

## Project Highlights

- **Hero & About** – Summarises applied scientist responsibilities, experience, and contact details.
- **Skills & Excellence** – Tailors the original template to focus on LLM strategy, generative AI programs, and insights leadership.
- **Gallery** – Curated imagery including Google I/O Connect and Amazon AnalyticCon appearances.
- **Blog & Video Content** – Two long-form Google I/O Connect videos plus a Shorts section with 9:16 embedded reels.
- **Calls-to-Action** – Cal.com booking buttons for collaborations and recruiter outreach.

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/shabul/seo_webistes_shabul.git
   ```
2. Install dependencies (none required – static HTML/CSS/JS only).
3. Open `index.html` directly in a browser, or serve the folder locally:
   ```bash
   python3 -m http.server 8080
   ```
4. Navigate to `http://localhost:8080` to view the site.

## Editing Tips

- **Styles** live in `css/style.css`; new custom rules are appended near the bottom.
- **Scripts** are in `js/main.js` (light modifications to the DevFolio behaviour).
- **Media** assets (images, Shorts, galleries) are stored under `img/` and referenced directly from `index.html`.
- **Video Embeds**: use YouTube’s `/embed/` URLs with explicit `width="315" height="560"` for Shorts to maintain 9:16 ratio.
- **Meetings CTA**: the Cal.com link is reused across the navbar, hero CTA, and footer — update all instances together if it changes.

## Deployment

The site is static and can be deployed to any static host (GitHub Pages, Netlify, Amazon S3 + CloudFront, etc.). Upload the contents of the repository as-is and ensure the `img/`, `css/`, `js/`, `lib/`, and `contactform/` directories are preserved.

## Attribution

- Base template: [DevFolio](https://bootstrapmade.com/devfolio-bootstrap-portfolio-html-template/) by BootstrapMade (MIT license).
- Additional libraries: Bootstrap 4, jQuery, Owl Carousel, Lightbox, Typed.js, and others included with DevFolio.

---

Questions or future changes? Reach out via the Cal.com booking link embedded on the site.
