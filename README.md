# Diyaverse 2026

A static, mobile-first website for the Business Department, DDU Diwali fest. The site uses plain HTML, CSS and vanilla JavaScript, with no build step or server dependency.

## Deploy on GitHub Pages

In the repository's **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**. The workflow then deploys the static site whenever changes are pushed to `main`, and can also be run manually from the repository's **Actions** tab. It publishes the repository root; no build step is needed.

After the first successful deployment, the site is available at <https://animesh-cloud-dev.github.io/diyaverse-2026/>.

Before promoting the event, replace the `[FEST_HASHTAG]` placeholder in `index.html` with the official hashtag. The **Share this site** button creates a WhatsApp message with the current page URL. All local asset paths are relative, so the site works from its GitHub Pages project URL as well as when `index.html` is opened directly.
