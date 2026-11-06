# Sonixy SEO setup

The GitHub Pages site is published at https://nourddinak.github.io/sonixy/.

## Included

- `sitemap.xml` lists the canonical public website URL for search crawlers.
- `robots.txt` allows crawling and advertises the sitemap.

## After deployment

1. Confirm `https://nourddinak.github.io/sonixy/robots.txt` and `https://nourddinak.github.io/sonixy/sitemap.xml` load successfully.
2. In Google Search Console, add the GitHub Pages URL-prefix property, verify ownership using the existing HTML verification meta tag on the homepage, and submit `sitemap.xml`.
3. In Bing Webmaster Tools, add the site and submit the same sitemap. You can also import the verified Google Search Console property.
4. Check the URL with Google's Rich Results Test and PageSpeed Insights, and fix any reported issues.

The site currently has one public HTML page, so the sitemap intentionally lists only the homepage. Add public, canonical pages to the sitemap when they are created; do not include release binaries or private/duplicate URLs.
