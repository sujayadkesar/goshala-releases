# Goshala Ledger — releases

Build output only. This repository exists so the app can fetch its own
updates: it is public, and the repository holding the source is not,
because that one carries nightly backups containing donor records.

- `version.json` — the manifest every phone reads at launch.
- Release assets — the web bundle for each version, and the APK.

Nothing here is edited by hand. It is written by `release-bundle.yml`
in the source repository.
