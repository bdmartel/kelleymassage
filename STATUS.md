# kelleymassage.com

## Status: Awaiting DNS Switch

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
- CNAME file temporarily removed for preview at bdmartel.github.io/kelleymassage

## Pages
- Home, Location and Contact, My Massage, My Philosophy (/about-me/), Rates and Reviews, Services
- Sidebar with bio, LinkedIn, Facebook, Yelp links

## Migration Checklist
- [x] Scrape all content from WordPress site
- [x] Download all images (studio, profile, flower, social icons, background)
- [x] Build static pages matching original design (Papyrus font, teal/salmon theme)
- [x] Create GitHub repo and enable Pages
- [x] DNS zone file prepared
- [ ] Add CNAME file back to repo before DNS switch
- [ ] Update DNS A records at GoDaddy
- [ ] Verify site loads on kelleymassage.com
- [ ] Enable HTTPS enforcement after DNS propagates
- [ ] Cancel GoDaddy hosting plan
