# Wallust

Placeholder website at https://www.wallust.com/ (also reachable at
https://wallust.com/). GitHub Pages publishes `main:/docs` with HTTPS enforced.
The custom domain belongs to this repository, so unrelated projects remain at
`https://jpxor.github.io/<repository>/`.

Edit `docs/index.html` to change the placeholder. Keep `docs/CNAME` set to
`www.wallust.com` and preserve domain ownership verification in DNS. The domain
was moved from the account repository on 2026-10-22; no DNS record changes were
needed.

The `docs/secrets/` files are temporary copies of Secrets' already-public
homepage/privacy/support pages, retained during Google branding verification.
Secrets' authoritative website is https://jpxor.github.io/secrets/ and its source
is https://github.com/jpxor/secrets. Once Google publishes the replacement
branding, replace the compatibility HTML with redirects to the corresponding
new pages. No application data belongs in this repository.

Other old project roots redirect to their github.io sites. `docs/404.html`
preserves deep links for the known project prefixes using a fixed github.io
destination. These browser redirects do not return HTTP 301 responses.
