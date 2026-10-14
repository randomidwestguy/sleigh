# Sleigh

A free holiday gift tracker. Everything runs in the browser and each family's list is saved in their own browser's local storage. There is no server, database, or account.

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `fonts/` | Be Vietnam Pro and Grand Hotel, self-hosted so no visitor data goes to Google (licenses included) |
| `js/xlsx.full.min.js` | Spreadsheet export library, self-hosted (license included) |
| `favicon.svg` | Browser tab icon |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Home Screen icons |
| `manifest.webmanifest` | Lets phones add Sleigh to the Home Screen as a full-screen shortcut |
| `og-image.png` | Preview image when the link is shared in texts or social posts |

## Domain

Link previews point to https://sleigh.fun. If the address ever changes, update the `og:url`, `og:image`, `twitter:image`, and canonical tags near the top of `index.html`.

## Putting it online (free)

**Netlify (easiest):** go to app.netlify.com/drop and drag this whole folder onto the page. It gives you a live address in seconds. You can connect your own domain in Site settings.

**GitHub Pages:** create a public repository, upload everything in this folder, then go to Settings, Pages, and choose the main branch.

**Cloudflare Pages:** create a project, choose "Upload assets," and drop the folder in.

All three serve over HTTPS, which browsers require for saving and copying to work properly.

## Keeping the privacy promise true

The footer says there is no tracking. If you add analytics later, pick a cookieless one such as Plausible or Simple Analytics, and update the footer wording to match.
