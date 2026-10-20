# Personal Google Drive desktop connection

A small informational site for janusnaefus's personal Google Drive connection
using [rclone](https://rclone.org/).

- Homepage: https://janusnaefus.github.io/google-drive-desktop/
- Privacy policy: https://janusnaefus.github.io/google-drive-desktop/privacy.html

The site describes the connection's purpose and data handling for the Google
OAuth application information. It has no backend, sign-in flow, analytics, or
access to Google Drive data.

## Publishing

GitHub Pages publishes the repository root on the `main` branch.
The `.nojekyll` file keeps the HTML and CSS as plain static files.

Edit `index.html`, `privacy.html`, or `style.css` and push to `main` to update
the site.

## Local preview

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/.

## Credentials

Keep OAuth client JSON files, rclone configurations, authorization tokens, and
Google Drive files on the local computer. They do not belong in this public
repository.
