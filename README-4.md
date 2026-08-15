# Flip & Fix 🔧

A free, browser-based tracker for salvaging and reselling washers and dryers picked up off Craigslist. No server, no account, no database — everything runs locally in your browser.

## What it does

- **Log pickups** — track type, brand/model, source, condition, and known issues for every unit you bring home
- **Photo attachments** — attach multiple photos per unit so you can see condition at a glance
- **Search & filter** — quickly find units by model, brand, source, or status
- **Parts cross-reference** — automatically matches units that "Need Parts" against your "Donor Machine" units, flagging same-brand/same-type matches as likely swaps
- **Parts lookup links** — one-tap search links to iFixit, PartSelect, and RepairClinic pre-filled with the unit's model number
- **Affordable parts resources** — quick links to Parts Dr, Appliance Parts Pros, Reliable Parts, and Ben's Appliances
- **Craigslist free-section shortcut** — jump straight to your local free appliance listings
- **Resale price estimator** — rough estimated resale value per unit based on type, brand tier, and condition
- **Sale scheduler** — set a date, time, location, and asking price for a sale; upcoming sales are listed with color-coded urgency
- **Sold history** — a running log of what sold, when, and for how much

## How to use it

1. Open `index.html` in any web browser (Chrome, Safari, Firefox, Edge)
2. Start logging your pickups — no setup, no sign-in

If this repo is hosted via GitHub Pages, just visit the live link instead.

## Important: where your data lives

All data is stored in your browser's local storage — **not** in the cloud or a shared database. That means:

- Your inventory is tied to the specific browser/device you're using
- Clearing your browser data will erase your inventory
- Switching browsers or devices won't carry your data over

This is a lightweight personal tool, not a synced multi-device app.

## Tech

Single self-contained HTML file — HTML, CSS, and JavaScript, no build step, no dependencies, no external services required to run.
