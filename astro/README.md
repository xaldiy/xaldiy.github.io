# Aldi — Astro-powered personal website

A landing page for [`aldi.js.org`](https://aldi.js.org/) that introduces [aldi.my.id](https://aldi.my.id/) and gives visitors an overview of the website's Astro `src/` structure.

## Publish on GitHub Pages

This project is intended for the repository `xaldiy/astro`.

1. Put `index.html` in the root of the repository.
2. Open **Settings → Pages** in GitHub.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you publish from (usually `main`) and the `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the site.

If you want the page available at `https://xaldiy.github.io/astro/`, the repository must be named `astro` and Pages must be configured to publish from that repository.

## Point `aldi.js.org` to GitHub Pages

Configure the domain's DNS according to the current GitHub Pages custom-domain instructions, then add `aldi.js.org` in the repository's **Settings → Pages → Custom domain**. Follow the DNS records GitHub shows for your setup and wait for DNS propagation before enabling HTTPS.

## About

The page uses plain HTML and CSS, with a tiny JavaScript snippet for the current year. It does not require an Astro build or npm dependencies, so it can be published directly as a static GitHub Pages site.

The source-tree view is an intentionally abbreviated overview of the `src/` tree supplied for this page; it is not a complete file explorer.
print(f"Created: {outdir / 'index.html'}")
print(f"Created: {outdir / 'README.md'}")
