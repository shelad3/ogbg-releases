# OGBG releases

Public release manifest and installers for the OGBG app.

- `release.json` — update manifest the app reads over HTTPS.
- `releases/` — installers attached to each GitHub Release.

Source code for the app is **not** public and lives in a private repository.
Release binaries are public because the in-app updater downloads them
anonymously, and a private GitHub repository would require an auth token that
a distributed app cannot safely carry.

Verify any installer before installing it:

    sha256sum -c SHA256SUMS
