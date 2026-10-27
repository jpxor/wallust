# Wallust

Placeholder website at https://www.wallust.com/ (also reachable at
https://wallust.com/). GitHub Pages publishes `main:/docs` with HTTPS enforced.
The custom domain belongs to this repository, so unrelated projects remain at
`https://jpxor.github.io/<repository>/`.

Edit `docs/index.html` to change the placeholder. Keep `docs/CNAME` set to
`www.wallust.com` and preserve domain ownership verification in DNS. The domain
was moved from the account repository on 2026-10-22; no DNS record changes were
needed.

The `docs/secrets/` directory contains only the static homepage and privacy
policy needed for Secrets' Google OAuth branding on the verified wallust.com
domain. These pages stay directly accessible, with canonical URLs pointing to
https://jpxor.github.io/secrets/ and its privacy page. The full website,
downloads and recovery/support remain in https://github.com/jpxor/secrets.
No application data belongs in this repository.

Other old project roots redirect to their github.io sites. `docs/404.html`
preserves deep links for the known project prefixes using a fixed github.io
destination. These browser redirects do not return HTTP 301 responses.
