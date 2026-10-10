# Stillcairn website

Static public website for the Stillcairn iPhone app. The app source is kept in a separate repository.

## Positioning

**Your card. Your boundaries. Your time.** Stillcairn uses standard writable NFC cards, local pairings and recorded session insights. The site describes a product being prepared for public release and has no checkout, testimonials, user-count claims, analytics scripts or fake email form.

## Local preview

Run `python3 -m http.server 8080` in this directory and open `http://localhost:8080/`.

## Publishing

The site deploys through GitHub Pages from `main` / root. Cloudflare hosts the DNS-only `focus.cybrpulse.com` CNAME pointing to `tom-gorup.github.io`, matching the existing Practice Studio setup. GitHub Pages handles the site's HTTPS certificate.

Contact mail links use the already configured `support@cybrpulse.com` and `privacy@cybrpulse.com` routing addresses.

The privacy and support pages are `privacy.html` and `support.html`. Review both against the current app source, especially Family Controls and optional parent controls, before changing their copy. The CybrPulse domain supplies information and routed support addresses; it does not establish the Apple seller identity. Publishing is a push to `main`; verify HTTPS, links, and mobile layout afterward.
