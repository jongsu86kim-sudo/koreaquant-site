# KoreaQuant public website

This repository contains **only public informational web pages** for KoreaQuant.
The quant trading research code, historical market data, Google Drive credentials,
and API keys remain in a separate private repository.

## Pages publishing

1. Open [Settings → Pages](https://github.com/jongsu86kim-sudo/koreaquant-site/settings/pages).
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. Check the Pages configuration for the active published URL, expected to be:
   https://jongsu86kim-sudo.github.io/koreaquant-site/
5. Privacy-policy URL after Pages becomes active:
   https://jongsu86kim-sudo.github.io/koreaquant-site/privacy.html

## Files

- `index.html` — KoreaQuant project homepage
- `privacy.html` — current static website privacy notice, with future Drive integration disclosed as planned
- `terms.html` — project / investment disclaimer
- `style.css` — no dependencies or external trackers

## Important OAuth limitation

GitHub Pages publishing is **not** proof that the project controls `github.io`.
Google OAuth production verification can require ownership of the homepage's
domain in Google Search Console. Do not put `github.io` into Google's
authorized domains assuming it will pass. This requires further review and
possibly a domain you own.

Do not add tokens, account data, private repository contents, or financial
reports to this public repository.
