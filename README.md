# Fyzzle public website

This is a static GitHub Pages site. It provides the App Store marketing, support, and privacy-policy pages.

## Before publishing

The support and privacy pages use `rich.dodzi11@gmail.com` as their contact address.

After Fyzzle is live on the App Store, replace the disabled App Store button in `index.html` with the real App Store product URL.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository named `fyzzle-site`.
2. Upload everything in this folder to the repository root.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/(root)`, and save.
5. Wait for the Pages deployment to finish.

Your App Store Connect URLs will be:

- Marketing: `https://YOUR-GITHUB-USERNAME.github.io/fyzzle-site/`
- Support: `https://YOUR-GITHUB-USERNAME.github.io/fyzzle-site/support/`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/fyzzle-site/privacy/`

Later, when you own a custom domain, point it to GitHub Pages and use:

- `https://fyzzle.app/`
- `https://fyzzle.app/support/`
- `https://fyzzle.app/privacy/`
