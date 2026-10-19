# Dokusho extensions

Published extension index for [Dokusho](https://github.com/Globeeeee/dokusho), the Android
web novel reader. This branch is written by CI from
[dokusho-extensions-source](https://github.com/Globeeeee/dokusho-extensions-source); do not
edit it by hand.

## Add to Dokusho

Settings → Browse → Extension repos → Add, then paste:

```
https://github.com/Globeeeee/dokusho-extensions/raw/repo/index.pb
```

## Status

Empty. The first extensions are published when the app reaches phase 1.

## The three repos

| Repo | Role |
|------|------|
| [dokusho](https://github.com/Globeeeee/dokusho) | the app |
| [dokusho-extensions-source](https://github.com/Globeeeee/dokusho-extensions-source) | extension source code |
| [dokusho-extensions](https://github.com/Globeeeee/dokusho-extensions) | this index |

## Files

| File | Role |
|------|------|
| `index.pb` | gzipped protobuf index, the URL the app reads |
| `index.json` | same data, readable |
| `repo.json` | repo name, website and APK signing key fingerprint |
| `index.html` | plain list of APK links |
| `index.min.json` | legacy stub for old app versions |
| `icon/` | fallback icons |

APKs and JARs are attached to GitHub Releases of this repo, not committed to the branch.

## Requests

Ask for a site in [dokusho-extensions-source issues](https://github.com/Globeeeee/dokusho-extensions-source/issues).
