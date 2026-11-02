# Fortune Group Technologies — independent website

Standalone public static export of the Fortune Group Technologies website as of 2 November 2026.

## Provenance
- Source: owner-controlled website at https://fortune-group-technologies.floot.app/; published server-rendered HTML and CSS.
- Static files: `public/index.html`, `public/styles/` and self-hosted `public/_cdn/static/` assets.
- Independent copy excludes “Made with Floot” overlay, Floot JavaScript runtime and analytics. Native JavaScript handles mobile navigation.
- Existing FortuneFlo, Double Infinity, legal and contact details preserved.

## Zero-additional-cost hosting
- Render static site: use `render.yaml`, or choose build command `echo "Static export; no build required"` and publish path `public`.
- Inspect deployed page visually on desktop/mobile; confirm all images, links, text and mobile navigation.
- Attach `fortunegrouptechnologies.co.uk` only after independent preview passes. In LCN DNS, preserve MX, SPF, DKIM and any other mail records; use exact DNS targets shown by Render.
- Require valid HTTPS, apex and www, and 200 responses before replacing the Floot link.

## Evidence status
BUILT: export, CSS, self-hosted assets and hosting configuration.
OPEN: independent-host deployment, rendered visual acceptance, DNS/TLS cutover.
Floot remains live unchanged until migration is proven and accepted.
