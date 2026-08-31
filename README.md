# Notion Architecture Canvas

An interactive version of Notion's three-layer architecture diagram (Collaboration / Agent / Context)
for use on sales calls. Reps can tailor the visible tool logos to each customer's stack.

**Live page:** https://<your-username>.github.io/<repo-name>/

## How reps use it
- **Tailor** (top right) — pick the customer's tools; the diagram updates live.
- **Customer name** — shown in the header as "Notion × <Customer>".
- **Saved setups** — save a selection per account and reapply it in one click.
- **Add your own logo** — upload an image or make an initials tile for a tool that isn't listed.
- **Present** — hides all controls for a clean screen-share.
- **Copy image** — grab the diagram as an image for a follow-up email.

## How to update the page
Replace `index.html` in this repo with a new version and commit. GitHub Pages redeploys
automatically in about a minute (hard-refresh the page to see changes).

## Notes
- Single self-contained file — no build step, no backend.
- Per-rep settings (saved setups, custom logos, customer selection) are stored in each
  person's own browser, so each rep's setup is private to them and survives refreshes.
