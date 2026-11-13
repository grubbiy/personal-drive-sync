# Personal Drive Sync

Static homepage, privacy policy and terms for a personal rclone Google Drive configuration. This repository contains public information pages only.

## Publish

Upload `index.html`, `privacy.html`, `terms.html`, `style.css` and `.nojekyll` to the `main` branch of the public `grubbiy/personal-drive-sync` repository. In repository Settings → Pages, choose Deploy from a branch, main, /(root), then Save.

After Pages finishes deploying, check these expected URLs before using them in Google Auth Platform:

- Homepage: https://grubbiy.github.io/personal-drive-sync/
- Privacy policy: https://grubbiy.github.io/personal-drive-sync/privacy.html
- Terms: https://grubbiy.github.io/personal-drive-sync/terms.html
- Authorized domain: grubbiy.github.io

Set the Google OAuth app name to `Personal Drive Sync` so it matches these pages.

Do not commit OAuth client secrets, rclone configuration, tokens or Drive files to this public repository.
