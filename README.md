# Hamilton Place Partners website

Static site for hamiltonplacepartners.com. Plain HTML, no build step.

- `index.html`: home page
- `about/index.html`: About page
- `thanks/index.html`: confirmation page shown after the contact form is sent
- `assets/`: images, including `og-image.png` (the 1200x630 preview shown when a link is shared) and `apple-touch-icon.png`
- `robots.txt`, `sitemap.xml`: for search engines
- `netlify.toml`: tells Netlify to publish the files as they are

Netlify deploys automatically on every push to `main`.

The "Book a call" contact form on both pages is handled by Netlify Forms (form name `book-a-call`); submissions appear under Forms in the Netlify project.

Still to add: LinkedIn links, privacy policy page.
