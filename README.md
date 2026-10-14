# MeetSimpler root redirect

This repository serves https://meetsimpler.github.io/ and redirects visitors to
https://meetsimpler.github.io/meetsimpler-web/.

GitHub Pages publishes the root of the `main` branch. The redirect uses JavaScript
to preserve query parameters and fragments, with an immediate HTML refresh and a
clickable link as fallbacks. This is a browser redirect, not an HTTP 301 response.

The actual website remains in the separate `meetsimpler-web` repository.

`robots.txt` is served at the domain root and points crawlers to
https://meetsimpler.github.io/meetsimpler-web/sitemap.xml. Keep this URL synchronized
with the website repository if the website location changes.
