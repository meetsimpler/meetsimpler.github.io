# MeetSimpler root redirect

This repository serves https://meetsimpler.github.io/ and redirects visitors to
https://meetsimpler.github.io/meetsimpler-web/.

GitHub Pages publishes the root of the `main` branch. The redirect uses JavaScript
to preserve query parameters and fragments, with an immediate HTML refresh and a
clickable link as fallbacks. This is a browser redirect, not an HTTP 301 response.

The Google verification file is served directly at
https://meetsimpler.github.io/google91257e2d5f746e32.html.

The actual website remains in the separate `meetsimpler-web` repository.
