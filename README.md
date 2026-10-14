# MBB APPS Website — GitHub Pages

## Files
- `index.html` — main responsive developer website
- `privacy.html` — privacy policy starter template
- `terms.html` — terms of service starter template

## Before publishing
1. Open `index.html` and replace `REPLACE_WITH_SUPPORT_EMAIL` with your real support email.
2. In the `apps` array near the bottom of `index.html`, replace each placeholder `storeUrl: "#"` with the exact public Google Play or App Store URL.
3. Remove or rename example entries that do not match your real apps. Add every app you want to show using the same object format.
4. The six currently discovered MBB APPS listings are included in `index.html`. Their buttons currently open your official Google Play developer page; replace each `storeUrl` with that app's individual Google Play URL when available.
5. Customize `privacy.html` so it accurately describes your apps, SDKs, permissions, data collection and privacy practices. Do not publish the template unchanged.
6. Customize `terms.html` and add the correct last-updated date.
7. Check every link on mobile and desktop.

## Publish using GitHub Pages
1. Sign in at https://github.com and create a new **public** repository, for example `mbb-apps-website`.
2. Upload `index.html`, `privacy.html`, `terms.html`, and this README to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish. The address will look like `https://YOUR-USERNAME.github.io/mbb-apps-website/`.
7. If you want the root URL `https://YOUR-USERNAME.github.io/`, name the repository exactly `YOUR-USERNAME.github.io`.

## Important
This is a static website. No backend or paid hosting is required for basic GitHub Pages hosting. A custom domain is optional.
