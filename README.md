# AidingMigraine-Welcome

Welcome page for [Aiding Migraine](https://aidingmigraine.com/) — the closed-beta
front door for the personal migraine journal.

- Live site (once DNS is set): https://aidingmigraine.com/
- The app itself lives at https://app.aidingmigraine.com/
  (PWA repo: [AidedMarketing/AidingMigraine](https://github.com/AidedMarketing/AidingMigraine))

## What this is

A single static page (`index.html`, inline CSS, no JavaScript, no backend,
no analytics, no tracking). Calm, low-stimulation, migraine-safe design:
muted colours, no flashing, no animation, no pop-ups, no autoplay.

## Deploy

GitHub Pages, `main` branch, root. `CNAME` contains `aidingmigraine.com`.

**Order matters:** set the GoDaddy DNS records first (apex A/AAAA to GitHub
Pages, `www` CNAME to the apex), verify the domain resolves to GitHub's
Pages IPs, *then* enable Pages with the custom domain. Adding the CNAME
before DNS points at GitHub makes the site unreachable.

## Copy rules

The disclaimer on the page is verbatim from the app — do not paraphrase it.
No medical claims anywhere: no "reduce", "prevent", "relieve", "treat", or
"manage your migraines" language. The app is a personal diary, not medical
advice.

## Status

- Nov 12, 2026: DNS live. App subdomain live over HTTPS. Apex HTTPS
  certificate provisioning retriggered with this commit.
