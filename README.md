# Bonk Royale 3D: public website

This folder is the whole website. Friends without claude.ai can play from it on any device with internet.

| Address | Track |
|---|---|
| `/` | Stable (main) |
| `/beta/` | Beta |
| `/alpha/` | Alpha (newest features) |

Multiplayer on the website connects devices directly (WebRTC). A free PeerJS matchmaking service introduces the devices. If a network blocks direct links, a free relay is used, and you can add your own relay in Settings → 🌐 Multiplayer.

Safety:
- The host must tap ✅ Allow before anyone joins.
- Chat is off unless the host turns it on.
- Swear words are hidden in English, Spanish, French, Portuguese, German and Italian, in chat and in names.

## Putting it online for free (GitHub Pages)

1. Make a free account at github.com (a grown-up should do this).
2. Click **+** → **New repository**. Name it, for example, `bonk-royale`, choose **Public**, and click **Create repository**.
3. Click **uploading an existing file**. Drag in everything inside this `website` folder (`index.html`, and the `beta` and `alpha` folders), then click **Commit changes**.
4. Go to **Settings** → **Pages**. Under *Branch*, pick **main** and **/ (root)**, then click **Save**.
5. After a minute the site is live at `https://YOUR-NAME.github.io/bonk-royale/`. Beta is at `…/bonk-royale/beta/` and Alpha at `…/bonk-royale/alpha/`.

To update later, upload the new files the same way. Claude rebuilds this folder whenever a track changes.

Netlify Drop (app.netlify.com/drop) also works: drag this folder onto the page.

## License

None. Copyright © 2026 hawkism. **All rights reserved.** See [LICENSE](LICENSE). The files are public only so GitHub Pages can serve the game; that does not grant any right to copy or reuse them.
