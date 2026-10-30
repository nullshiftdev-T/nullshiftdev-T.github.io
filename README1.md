# NULLSHIFT Website

A complete, responsive, spoiler-safe static website for **NULLSHIFT**, built with plain HTML, CSS, and JavaScript.

## Files

- `index.html` — the full website
- `styles.css` — responsive styling and visual system
- `script.js` — mobile navigation, development peek tabs, and two mini ARG puzzles
- `favicon.svg` — site icon
- `NULLSHIFT_LICENSE.md` — the project's supplied license notice

## Run locally

Open `index.html` in a modern browser. No build step, package manager, server, or framework is required.

For a local server, run this from the website folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Open the repository used for `https://nullshiftdev-t.github.io/`.
2. Back up the current website files.
3. Upload the contents of this folder to the repository's publishing root.
4. Keep the file names and folder structure unchanged.
5. In the repository settings, make sure GitHub Pages is publishing from the correct branch and root folder.
6. Open the site and test it on both desktop and mobile.

The site is deliberately framework-free, so GitHub Pages can serve it directly.

## Spoiler policy

The public site intentionally avoids plot reveals and deeper canon terminology. The two Signal Room puzzles are standalone website puzzles and are not required to understand the game.

## Privacy and functionality

- No analytics or tracking scripts are included.
- Puzzle progress is held in page memory only and resets when the page is reloaded.
- There is no account system, contact form, backend, or database.
- Google Fonts are loaded from Google's font CDN; system fallbacks are included.

## Updating the site

Edit the visible copy in `index.html`.
Update visual styles in `styles.css`.
Change the peek cards or puzzle answers in `script.js`.

Keep the public copy spoiler-safe when adding new material.