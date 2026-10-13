# Hall Pilot website

Public marketing website for **Hall Pilot**, digital hall-pass management for schools.

- **Website:** https://hallpilot.net/
- **Application:** https://app.hallpilot.net/
- **Separate live application repo:** `scottxian/wusd-hall-pass`

This is a static GitHub Pages site. It has no access to student data or Supabase credentials.

## Deploy

Go to **Settings → Pages**, set **Deploy from a branch**, choose **main** and **/(root)**. The `CNAME` file configures `hallpilot.net`; DNS and HTTPS require separate verification.

Do **not** edit the live application's custom domain or DNS record for `app.hallpilot.net`.

Brand assets, favicons, responsive CSS, and a plain-text deployment README are included in this repo.