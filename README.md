# Building Tilth — landing page starter

**Building Tilth: Technical Assistance for Community Agency**

This is a lightweight, accessible, responsive homepage intended as an early public reference for a developing practice in community technical assistance, applied research, and organizational capacity-building.

The two experience sections describe **prior project areas informing the practice**. They deliberately do **not** claim specific clients, outcomes, or contracts conducted under the Building Tilth name. Edit these sections as you develop approved case studies.

## Files

- `index.html` — GitHub Pages homepage (no JavaScript or build system).
- `styles.css` — all site styling, responsive layouts, and accessibility adjustments.
- `assets/favicon.svg` — simple, editable root-and-sprout brand icon.
- `.nojekyll` — tells GitHub Pages to serve the files as plain static assets.
- `wordpress-content.html` — HTML for a WordPress Custom HTML block (without site header/footer or SVG graphics).
- `wordpress-styles.css` — WordPress-scoped CSS, designed to avoid changing your theme's other pages.
- `CONTENT.md` — quick-to-edit summary of current copy and future additions.

## Publish on GitHub Pages

1. Create or sign into a GitHub account at <https://github.com>.
2. Create a new **public** repository, for example `building-tilth`. (If the account is on GitHub Free, public visibility is required for GitHub Pages.)
3. Upload the **contents of this folder** to the repository root, preserving `index.html`, `styles.css`, `assets/`, and `.nojekyll`.
4. In the repository, visit **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, `main`, and `/(root)`, then save.
5. After GitHub processes the deployment, the expected project-site URL is `https://YOUR-USERNAME.github.io/building-tilth/` (replace the example username and match the actual repository name). Look at the Pages setting for the confirmed live URL.
6. Use that confirmed URL on your CV. If you later buy a domain, set it up in GitHub Pages and add the DNS records requested by GitHub.

GitHub's current documentation: <https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site>

**Important:** The repository and site are **not** published by producing these files. You must publish them using your GitHub account, or connect the GitHub integration so an authorized publishing workflow can be completed.

## Use with WordPress later

This design is built with standard HTML and CSS, so the content and styling are portable without any framework, build step, or license-restricted fonts.

1. Create a WordPress Page and ideally choose a full-width/blank page template.
2. Add a **Custom HTML** block and paste the contents of `wordpress-content.html`.
3. In your site editor, add `wordpress-styles.css` under your site's **Additional CSS** options (the exact location depends on your WordPress version and theme).
4. Preview on desktop and mobile. Your theme may add gutters, fonts, or headings; adjust accordingly.
5. Replace the supplied project descriptions and contact copy as the practice evolves.

The WordPress variant omits inline SVG artwork because some installations strip SVG or disallowed HTML. The original GitHub design remains the master reference. WordPress capabilities and plans differ; users without the appropriate permissions may have HTML, CSS, or JavaScript filtered.

Official docs: <https://wordpress.org/documentation/article/custom-html/> and <https://wordpress.org/documentation/article/styles-overview/>

## Quick changes before publishing

- **Contact**: The current section explicitly points visitors back to the CV/professional profile. Replace the paragraph beginning `For now, please use the contact details...` with a real professional email or contact link when you choose one. Avoid putting private contact details in a public GitHub repository unless you're comfortable with that.
- **Project details**: Confirm that each summary reflects your work and permissions to discuss it. Do not add names of clients or specific impacts without consent and evidence.
- **Status**: Change `emerging practice` and `independent practice in development` only when appropriate.
- **Location**: The current copy says Ann Arbor area, Michigan; edit as desired.
- **Brand/legal**: The prior naming discussion surfaced possible related TILTH trademarks and businesses. Publishing a web page does not legally clear or register the name. Obtain an appropriate clearance review before treating the brand as protected or formally operating under it.

## Accessibility and privacy

Semantic HTML, keyboard focus indicators, skip link, mobile layouts, and reduced-motion support are included. No tracking scripts, cookies, external fonts, forms, or remote dependencies are used.

## A possible CV line

**Building Tilth — Technical Assistance for Community Agency** · Founder / Developing independent practice · [Website](https://YOUR-USERNAME.github.io/building-tilth/)

Replace `YOUR-USERNAME` only after the site is actually live. Consider `Independent initiative (in development)` instead of a formal business title until incorporation/launch status is determined.
