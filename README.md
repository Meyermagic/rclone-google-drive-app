# rclone-google-drive-app

Basic GitHub Pages boilerplate for the Google OAuth consent requirements mentioned in:
https://rclone.org/drive/#making-your-own-client-id

## Included pages

- Home page: `docs/index.md`
- Privacy policy: `docs/privacy.md`

## Enable GitHub Pages

1. Go to repository **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select your branch (for example `main`) and folder **`/docs`**.
4. Save and wait for Pages to publish.

Your site URL will be:

`https://<your-github-username>.github.io/rclone-google-drive-app/`

Use these URLs in Google Cloud Console:

- **Application home page**:
  `https://<your-github-username>.github.io/rclone-google-drive-app/`
- **Application privacy policy link**:
  `https://<your-github-username>.github.io/rclone-google-drive-app/privacy`

## Google OAuth setup note

After adding those links, add `github.io` to **Authorized domains**, save, then return to **Audience** and publish the app.
