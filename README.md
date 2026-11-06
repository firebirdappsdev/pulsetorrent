# PulseTorrent GitHub Pages bundle

Static HTML, CSS, and the existing PulseTorrent icon. No build, npm install, website Analytics, cookies, external fonts, or submission form is included.

Public URLs:

- https://firebirdapps.com/pulsetorrent/
- https://firebirdapps.com/pulsetorrent/privacy-policy.html
- https://firebirdapps.com/pulsetorrent/terms-of-use.html

The Android About panel already links to the two policy URLs. They become available after you publish these files.

## Upload

Choose the option matching your existing GitHub Pages setup:

1. **A separate project repository on the same GitHub account:** name the repository `pulsetorrent` (lowercase). Upload the **contents** of this folder to the repository root, including `assets/`, `styles.css`, and `.nojekyll`. In Settings → Pages, deploy from your chosen branch and `/ (root)`. If `firebirdapps.com` is configured on that account's user/organization Pages site, the project inherits that custom domain and appears at `/pulsetorrent/`.
2. **A folder in the repository that already serves firebirdapps.com:** copy the **whole `pulsetorrent/` folder** into its published root. If that site publishes from `docs/`, use `docs/pulsetorrent/`. Commit and push to its published branch.

Keep the existing domain configuration that serves FormsApp. This bundle intentionally contains **no CNAME**; do not redirect the apex domain to a new project or enter a URL with `/pulsetorrent` as a custom domain. Paths come from the repository name or directory layout, not DNS. GitHub may redirect `/pulsetorrent` to `/pulsetorrent/`.

All internal links and assets are relative, so either upload layout works. Preserve lowercase filenames. After publishing, open all three public URLs and check the logo, navigation, support email, and both Android About links.

## Content maintenance

The policies describe the implemented Android package `com.firebirdapps.pulsetorrent`, direct peer/tracker traffic, public file access, local history/reminders, Firebase Analytics (without an in-app opt-out), optional Realtime Database feedback, and existing deletion controls. Feedback records contain only stars, message, random record identifier, and server timestamp; they do not contain the additional FormsApp metadata fields.

The support address is reused from your published FormsApp site: `firebirdapps.dev@gmail.com`. Update the effective/last-updated dates and policy text when app behavior or data handling changes. Submit the Privacy policy URL in the Play Console as well as keeping the in-app link. Publishing these pages does not itself update Play Console declarations.
