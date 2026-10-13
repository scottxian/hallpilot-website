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


--------------------------------------------------
Website update — October 13, 2026
Type: UI, Navigation, Contact and App Access

Changes:
- Replaced non-scoped "Open app" links with school-link instructions.
- Added demo inquiries via info@hallpilot.net.
- Added support@hallpilot.net and customerservice@hallpilot.net contact links.
- Added a small-screen navigation menu and keyboard skip link.
- Corrected social preview image URLs to a file in this repository.
- Preserved existing website logo and favicon files.

Files changed:
- index.html
- styles.css
- README.txt

Testing:
- HTML anchor IDs and navigation references verified.
- All local asset references found in the repository.
- CSS brace balance and responsive menu rules checked.
- No root-only application links remain.
- Live browser and mail-client behavior still requires verification.

Application impact:
- No changes to app.hallpilot.net, Supabase, or the Hall Pass code.
