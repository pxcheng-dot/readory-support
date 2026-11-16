# ReadiBean

Marketing and support site for ReadiBean: Family Reading.

Live: `https://readibean.app/` (GitHub Pages, custom domain in `CNAME`). The old `https://pxcheng-dot.github.io/readory-support/` address redirects here.

- Home + support: `index.html`
- Privacy: `legal/privacy.html`
- Feature images: `images/` (1280 px WebP from the ReadiBean marketing set)
- Link preview image: `og-image.png` (1200 × 630)
- Icons: `favicon.ico` (16/32/48), `apple-touch-icon.png` (180), `icon-192.png`, `icon-512.png` (logo in structured data); `app-icon.png` is the nav wordmark
- Search: `robots.txt`, `sitemap.xml` (update `lastmod` when a page changes), `404.html` (not indexed)

`index.html` is the exported site, not the editor page. Publish the file from the editor's **Download index.html** button; never upload the editor artifact's own `index.html` or `content.json`, which drop the page's title, description, link preview and structured data.

The `<head>` holds the search title and description, link-preview tags and JSON-LD (WebSite, Organization, MobileApplication). The FAQ carries schema.org FAQPage microdata on the `<details>` elements, so edited answers stay in step with the structured data.

Support: [support@readibean.app](mailto:support@readibean.app)
