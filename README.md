# Vibe POC (Safe Ship)

This repo proves a non-technical person can publish real software safely using a step-by-step approval process.

## What this is
- A static website (HTML/CSS/JS) hosted on GitHub Pages
- No backend, no database, no accounts, no payments
- Lowest-risk possible “real” deployment

## Live site
GitHub Pages is enabled for this repo (Settings → Pages).

## Safe Ship Checklist (DO THIS EVERY TIME)
Before you publish anything public:

1) ✅ No secrets
- NEVER paste passwords, API keys, private links, invoices, or customer data into this repo.
- If you’re unsure whether something is a secret: treat it like a secret and don’t publish it.

2) ✅ No personal/private info
- Don’t include phone numbers, addresses, private emails, or anything you wouldn’t post publicly.

3) ✅ No backend until you’re ready
- Backend = higher risk (auth, databases, money, security updates).
- For early proofs, stay static.

4) ✅ Small change only
- Make one small change, publish, verify. Repeat.

5) ✅ Verify on the live URL
- Refresh the GitHub Pages URL after each commit and confirm it works.

## Rollback (undo mistakes)
- If you break the site, you can revert by restoring a previous version of `index.html` and committing again.

## Next upgrades (when ready)
- Add a contact form using a trusted third-party (no backend)
- Add a custom domain (optional; small cost)
- Move to a proper app platform only when payments or logins are needed
