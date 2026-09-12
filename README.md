# Relationship Mastery — prototype

A single self-contained HTML prototype of the Relationship Mastery mobile app. No build step, no dependencies, nothing server-side.

## Deploy on GitHub Pages

1. Create a new repository.
2. Upload the contents of this folder to the repository root: `index.html`, `manifest.webmanifest`, `apple-touch-icon.png`, `icon-512.png`, `.nojekyll`.
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
5. Wait about a minute. Your URL will be `https://<username>.github.io/<repo-name>/`.

## Install it on a phone

Open that URL in Safari (iOS) or Chrome (Android), then **Share → Add to Home Screen**. It launches fullscreen with its own icon, and the URL is permanent — unlike a temporary preview link.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole prototype — markup, styles, logic and fonts inlined, about 300 KB |
| `manifest.webmanifest` | Makes the home-screen install launch fullscreen on the dark ground |
| `apple-touch-icon.png` | 180px home-screen icon for iOS |
| `icon-512.png` | 512px icon for Android and PWA installs |
| `.nojekyll` | Tells Pages to serve the files as-is |

## Notes

This is a design prototype. Entries autosave while the app is open but do not persist across a reload or to any server — that belongs to the real build.

Curriculum content is drawn from the Relationship Mastery Reference Manual, © Jayson Gaddis LLC & The Relationship School® LLC.
