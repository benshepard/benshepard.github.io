# Ben Shepard | Flight Instruction

A custom, lightweight seven-page professional aviation website. Original design, text, and illustrated hero graphic. No website-builder subscription or build step required.

## Preview locally

Open `index.html` in a browser. For a local web server, run `python -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Publish to GitHub Pages

1. Create a **public** GitHub repository (for example `benshepard-site`).
2. Upload all files in this folder to the **root** of the repository, including the `assets` folder.
3. In repository **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Test the `https://YOUR-USERNAME.github.io/benshepard-site/` URL.
5. In **Settings > Pages > Custom domain**, enter `benshepard.com`.
6. At your domain registrar, configure GitHub Pages DNS according to its current documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site . Also configure `www` if desired.
7. Verify domain ownership as recommended by GitHub and enable **Enforce HTTPS** when available.

## MUST DO before public launch

- Confirm FAA instructor privileges and training authorizations. The CFI qualification is not claimed in the live text as a verified current fact.
- Confirm service region, airports, aircraft access, insurance arrangements, affiliations, and biography.
- Set actual rates and cancellation/payment policies in `rates.html`.
- **Contact form is deliberately not connected**. It will not send inquiries until configured. The current form uses a disabled mailto preparation flow with a placeholder email in `assets/site.js`. Replace it with your real email for mailto mode, or preferably connect a service like Formspree and update the form action/JS accordingly. Test a real submission before launch.
- Replace the original vector aircraft illustration with your own licensed aviation photography if desired.
- Review all regulatory and resource links against current FAA publications.
- Add privacy information appropriate to any form service and analytics used.

## Site pages

- `index.html` Home
- `about.html` About
- `instruction.html` Instruction
- `resources.html` Searchable resources and lesson references
- `faq.html` FAQ
- `rates.html` Rates & Policies
- `contact.html` Contact

## Editing

Colors, fonts, layout: `assets/styles.css`. Search/filter and contact behavior: `assets/site.js`. Copy: edit individual HTML pages. No React or npm dependency is required.
