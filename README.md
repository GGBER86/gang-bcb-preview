# Beyond the Booth — GanG of Spirits (BCB 2026 private preview)

Static site, no build step. `index.html` + PDF.

- Deploy: drag this folder to https://app.netlify.com/drop, or push to GitHub and connect the repo in Netlify (publish directory: `.`).
- Leads: the form posts to the Google Apps Script endpoint set in `window.GOS_CONFIG.endpoint` (inside index.html). Until it is set, answers are saved on the device and synced later.
- Update: replace `index.html` and redeploy (or push). The URL stays the same.
- QR tracking: add `?src=bcb-qr`, `?src=bcb-tablet`, `?src=followup`; team mode: `?mode=booth`.
