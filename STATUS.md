# kelleymassage.com

## Status: LIVE on GitHub Pages

## What
Static site for Kelley Massage Therapy (Sausalito, CA). Migrated from WordPress on GoDaddy SSH hosting to GitHub Pages.

## Stack
- Static HTML/CSS (multi-page, preserves WP URL structure)
- GitHub Pages hosting
- Custom domain: kelleymassage.com

## Repo
`bdmartel/kelleymassage` on GitHub

## DNS
- Registrar: GoDaddy
- Old hosting: GoDaddy SSH (216.70.90.24)
- New hosting: GitHub Pages (185.199.108-111.153)
- DNS A records already pointed to GitHub Pages (185.199.108-111.153)
- CNAME restored to repo 2026-03-09
- HTTPS cert approved, expires 2026-06-07
- HTTPS enforcement enabled
- MX record: 10 mail.kelleymassage.com (old server email, not migrated)
- www subdomain: no CNAME record set (only apex resolves)

## Pages
- Home, Location and Contact, My Massage, My Philosophy (/about-me/), Rates and Reviews, Services
- Sidebar with bio, LinkedIn, Facebook, Yelp links

## Migration Checklist
- [x] Scrape all content from WordPress site
- [x] Download all images (studio, profile, flower, social icons, background)
- [x] Build static pages matching original design (Papyrus font, teal/salmon theme)
- [x] Create GitHub repo and enable Pages
- [x] DNS zone file prepared
- [x] Add CNAME file back to repo before DNS switch (2026-03-09)
- [x] Update DNS A records at GoDaddy (already pointed to GitHub Pages IPs)
- [x] Verify site loads on kelleymassage.com (HTTP 200, serving from GitHub.com)
- [x] Enable HTTPS enforcement after DNS propagates (cert approved, enforced)
- [ ] Add www CNAME record pointing to bdmartel.github.io (optional)
- [ ] Verify email still works (MX points to mail.kelleymassage.com on old server)
- [ ] Cancel GoDaddy hosting plan (only after confirming everything works)
