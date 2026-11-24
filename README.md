# Scan Tool Field Guide

A responsive, US-focused informational website about automotive diagnostic scanners and equipment.

## Pages

- `index.html` — homepage
- `guides/index.html` — guide library / category hub
- `guides/bidirectional-scan-tools.html` — specification-based scanner comparison
- `guides/obd2-vs-bidirectional.html` — beginner explainer
- `guides/check-vehicle-compatibility.html` — pre-purchase compatibility checklist
- `about.html` — editorial standards
- `affiliate-disclosure.html` — affiliate status and disclosure policy
- `privacy.html` — starter privacy policy
- `assets/` — styles, navigation script and logo
- `robots.txt` — crawler rules and sitemap pointer
- `sitemap.xml` — canonical public URLs for search engines
- `404.html` — helpful not-found page, excluded from indexing

## Before applying to affiliate programs or promoting the site

1. Confirm brand availability and choose a domain; the brand name has not been trademark-cleared.
2. Add a real editorial contact email to the About and Privacy pages.
3. Recheck every product specification and exact US model/SKU against current manufacturer sources.
4. Apply to Amazon Associates and wait for approval before activating tagged Amazon links.
5. Once approved, display the required Amazon Associate statement and clear disclosures near affiliate links.
6. Add a sitemap and final-domain canonical URLs after the domain is selected.
7. Update the Privacy Policy before adding analytics, advertising, forms or other tracking.

## Editorial standards

Product comparisons in this initial release are desk research based on published specifications, not hands-on testing. Verify exact vehicle coverage for the make, model, year, trim, module and function before buying a scanner. Product capabilities, software policies and prices may change.

## Deployment

This is a static website and requires no build step. Enable GitHub Pages from the `main` branch and `/(root)` folder in repository Settings → Pages.

## Technical SEO baseline

The site currently includes unique page titles and descriptions, canonical URLs, Open Graph title/description metadata, JSON-LD for the website/organization, guide articles and breadcrumbs, a visible breadcrumb trail on guide pages, an XML sitemap, a sitemap reference in robots.txt, and a noindex custom 404 page. Internal links use descriptive anchor text and the pages are designed to work without client-side JavaScript for core content.

## Search Console follow-up

After confirming the Pages deployment is successful, add the exact Pages URL-prefix property in Google Search Console and submit:

https://mexiaeon.github.io/scan-tool-field-guide/sitemap.xml

URL inspection should be used to request indexing for the homepage, guide index and principal buying guide. Search Console is the source for actual crawl, indexing and performance reports; a valid sitemap does not guarantee that pages will be indexed or rank.

When a custom domain is selected, update canonical URLs, Open Graph URLs, JSON-LD URLs, sitemap URLs and the robots.txt sitemap line together before treating the custom domain as the primary site address.
