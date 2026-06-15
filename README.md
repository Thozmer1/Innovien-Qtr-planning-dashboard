# Innovien Q3 2026 Quarterly Planning Dashboard

Self-contained interactive dashboard (single `index.html`, no build step, no server).
All data is embedded in the file. **Treat this repository and deployment as confidential.**

## ⚠️ Confidentiality
This page contains internal placement, customer, spread, and AM/recruiter detail.
- Keep the GitHub repo **Private**.
- Enable **Deployment Protection** on Vercel (see below) so only your team can open the URL.
- `robots.txt` + `X-Robots-Tag` are set to keep it out of search engines, but that does NOT make it private — protection is required.

## Update process
Each refresh, replace `index.html` with the newest dashboard export and push:
```
git add index.html
git commit -m "Refresh dashboard data"
git push
```
Vercel auto-redeploys on every push to the default branch.

## Files
- `index.html` — the dashboard (open locally by double-clicking, or deploy)
- `vercel.json` — security headers + clean URLs
- `robots.txt` — discourage indexing
