# Publishing these files — FREE, not published yet
These 3 HTML files are built and sitting locally only. They are NOT live
on the internet yet, and no GitHub repo has been created for them.

## Publish route (GitHub Pages, ₹0)
1. On GitHub (account Nishantsingh11), create a NEW public repo, e.g.
   `milo-youtube-automation`. Do NOT put any token or secret files in it —
   only these 3 HTML files.
2. Upload index.html, privacy.html, terms.html to the repo root, branch main.
3. Repo > Settings > Pages > Build and deployment > Deploy from a branch >
   Branch: main, Folder: / (root). Save.
4. Wait a few minutes. The site will be at:
   https://nishantsingh11.github.io/milo-youtube-automation/
   Homepage: that URL.
   Privacy policy: https://nishantsingh11.github.io/milo-youtube-automation/privacy.html
   Terms: https://nishantsingh11.github.io/milo-youtube-automation/terms.html
   All three are on the same host, which is what OAuth verification asks for
   (privacy policy on the same domain as the homepage).

## Search Console verification — still to do at submission time
- In Google Search Console, verify the site as a URL-prefix property
  (nishantsingh11.github.io/milo-youtube-automation/) using the HTML file
  or meta tag Google provides at that time. That verification file/tag is
  NOT in this folder yet, because Google generates it when you start
  verification — add it then, it is not a secret.
- In Cloud Console > OAuth consent screen, add `nishantsingh11.github.io`
  as an authorised domain (the specific subdomain, not github.io itself),
  and set the homepage + privacy policy URLs above.
- Honest caveat: Google may still reject a shared-hosting subdomain.
  If it does, per Nishant's 2026-10-28 instruction, DO NOT buy a domain.
  Fallback: manual Studio public uploads + weekly token re-auth.

## Before publishing
Nishant must approve the exact wording of index.html, privacy.html, and
terms.html first — these pages will be public under his app name.
