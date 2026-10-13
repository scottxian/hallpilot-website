HALL PILOT PUBLIC WEBSITE
=========================

Repository: scottxian/hallpilot-website
Website domain: hallpilot.net
Application domain: app.hallpilot.net
Application repository: scottxian/wusd-hall-pass

CONTENTS
--------
- index.html and styles.css: static marketing website
- assets/hall-pilot-lockup.svg and assets/hall-pilot-mark.svg: scalable logo variants
- favicon.svg, favicon.ico, and favicon PNGs for desktop and mobile browsers
- apple-touch-icon.png and Android home-screen icons
- site.webmanifest, robots.txt, sitemap.xml, and browserconfig.xml
- CNAME: hallpilot.net
- .nojekyll: serves the site as plain static files

DEPLOYMENT
----------
Publish GitHub Pages from main / (root) under repository Settings > Pages.
Set the custom domain to hallpilot.net and enable Enforce HTTPS when available.
Point the apex hallpilot.net DNS records to GitHub Pages using the official A addresses.
Optionally point www.hallpilot.net to scottxian.github.io with a CNAME.
DO NOT change the existing app.hallpilot.net CNAME or the wusd-hall-pass repository.

VERSION / TESTS
---------------
Initial Hall Pilot marketing-site release, October 2026.
Repository file inventory and local HTML asset references verified.
Browser rendering and live production deployment remain to be tested after Pages and DNS are configured.

BRANDING
--------
The website includes a simplified SVG adaptation of the approved paper-airplane hallway concept and matching raster favicon/device icons. For an exact raster reproduction of the previously generated logo, use the approved source PNG in the design package and replace assets as desired.

SECURITY
--------
The public marketing repository must never include student roster information, PINs, service-role keys, or secret credentials.
