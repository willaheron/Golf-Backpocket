# Will's Golf — personal caddy app

A single-page web app: practice program, round book, hole-by-hole scorecard,
auto-updating handicap, bag & distances. All data is saved privately in your
phone's browser (localStorage) — nothing is sent anywhere, and it works offline
once loaded.

## Files
- `index.html` — the whole app (self-contained)
- `manifest.webmanifest` — makes it installable as an app
- `sw.js` — offline support, so the app opens on the course with no signal
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — home-screen icons

## Put it online with GitHub Pages (free)
1. Create a GitHub account if you don't have one, then **New repository** → name it
   e.g. `golf` → Public → Create.
2. On the repo page: **Add file → Upload files**, drag in all the files from this
   folder (index.html, manifest.webmanifest, the three png icons, this README),
   then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, Source = **Deploy from
   a branch**, Branch = **main**, folder = **/ (root)**, **Save**.
4. Wait ~1 minute, refresh. Pages shows your live URL, like
   `https://<your-username>.github.io/golf/`.

## Add it to your iPhone home screen
1. Open that URL in **Safari** (not Chrome).
2. Tap **Share** (□↑) → **Add to Home Screen** → name it *Golf* → **Add**.
3. Always open it from that icon so your data stays in one place.

## Back up your data
Rounds live only on the device. In the app: **More → Settings → Export** saves a
backup file; **Import** restores it (handy when switching phones).

## Alternatives to GitHub Pages
- **Netlify Drop** (app.netlify.com/drop) — drag the folder in, instant URL, no account needed to start.
- **Cloudflare Pages** — similar, free.

## Updating the app
Repo → Add file → Upload files → drop in the new file(s) with the exact same name → Commit changes.
GitHub replaces the old version; give it a minute, then close and reopen the app. Your rounds are untouched.
