# Navi-vis.tech Static Website

This is a dependency-free static website for Navi-vis.tech and its PathClear product.

## Files

- `index.html` — main landing page
- `styles.css` — dark navy/teal responsive styling
- `script.js` — small mobile navigation script
- `privacy.html` — starter privacy notice placeholder
- `terms.html` — starter terms placeholder
- `assets/navi-vis-logo.png` — official Navi-vis logo
- `assets/favicon.png` — favicon cropped from the logo
- `assets/pathclear-flow.svg` — workflow graphic

## Deploy options

### Netlify
1. Drag the folder into Netlify Drop, or connect your GitHub repo.
2. Set publish directory to the website root.

### Vercel
1. Import the repo.
2. Use static site deployment; no build command needed.

### GitHub Pages
1. Push the files to a repo.
2. Enable Pages from the main branch.

### Plain hosting
Upload all files to the web root of `navi-vis.tech`.

## Before production

- The public contact email is `contact@navi-vis.tech`.
- Replace privacy and terms pages with counsel-reviewed documents.
- Add analytics only if desired and disclosed.
- Add real product screenshots when available.
- Confirm regulatory wording with counsel / RA advisor.

## Regulatory wording note

The website intentionally uses "RA-review-ready", "evidence readiness", and "source-linked" language. It avoids claiming that PathClear provides FDA clearance, final regulatory decisions, or guaranteed submission readiness.


## Logo update

This package uses the supplied official Navi-vis logo image as `assets/navi-vis-logo.png`. The header and footer wrap the logo in a light logo plate so it remains legible on the dark navy site theme.


## Contact form delivery

The public contact form now posts to FormSubmit using `contact@navi-vis.tech` as the recipient. This makes the static site form work without a custom backend. On the first real submission, FormSubmit may send an activation/confirmation email to `contact@navi-vis.tech`; confirm it to start receiving inquiries.

The form includes a production thank-you redirect: `https://navi-vis.tech/thank-you.html`. If you deploy to a temporary preview URL, update the hidden `_next` field in `index.html` to match your preview thank-you page, or remove `_next` to use the provider's default confirmation page.

Do not ask users to upload confidential regulatory evidence through the public website form. Use the form only for inquiry and pilot scoping requests.
