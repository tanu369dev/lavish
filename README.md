# Marque Row

A luxury motorcycle marketplace. Browse and filter bikes, open a spec sheet, request a reservation, and list your own bike.

Plain HTML, CSS and JavaScript. No build step and no dependencies.

## Files

- `index.html` - the whole site (markup, styles, script and listing data)
- `img/` - bike photos
- `.nojekyll` - tells GitHub Pages to serve the files as they are

## Run locally

Open `index.html` in a browser.

## Put it on GitHub Pages

1. Create a new repository on github.com.
2. Upload everything in this folder (`index.html`, `README.md`, `.nojekyll` and the `img` folder).
3. Open the repository's Settings, then Pages. Under Build and deployment choose Deploy from a branch, pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Add or change a bike

Listings are the `samples` array near the top of the script in `index.html`. Copy one entry, give it a new `id`, and set `photo` to a file in `img/`.

## Limits

Listings added through the Sell form are saved in the visitor's own browser only. Reservations and payments are not connected to anything. Real shared listings, accounts and payments need a backend.
