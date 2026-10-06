# FocusKey website

Static public website for the FocusKey iPhone app. The app source is kept in a separate repository.

## Positioning

**Your card. Your boundaries. Your time.** FocusKey uses standard writable NFC cards, local pairings and recorded session insights. The site describes a private-testing product and has no checkout, testimonials, user-count claims, analytics scripts or fake email form.

## Local preview

Run `python3 -m http.server 8080` in this directory and open `http://localhost:8080/`.

## Publishing

The site deploys through GitHub Pages from `main` / root. Cloudflare hosts the DNS-only `focus.cybrpulse.com` CNAME pointing to `tom-gorup.github.io`, matching the existing Practice Studio setup. GitHub Pages handles the site's HTTPS certificate.

Contact mail links use the already configured `support@cybrpulse.com` and `privacy@cybrpulse.com` routing addresses.
