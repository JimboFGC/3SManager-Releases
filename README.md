# 3SManager releases

Official Windows downloads for **3SManager**, the tournament and broadcast manager formerly named 3SHub. This is separate from the netplay app now named 3SHub.

## Updating an existing installation

Open **Settings > Updates & backups > App updates** and check for updates. The updater selects your edition and preserves players, event history, profiles, settings, connections, organizer logos and OBS paths. It creates a rollback snapshot before replacing application files.

Older generic updaters may offer **Repair edition files** after their first update; this restores matching edition artwork without replacing saved data. Keep the application folder together. Do not overwrite an existing installation by manually extracting a clean ZIP over it.

The old `JimboFGC/3SHub-Releases` address redirects here. It must never be recreated or used for the netplay application.

## Downloads

Use the [latest release](https://github.com/JimboFGC/3SManager-Releases/releases/latest).

- `3SHub-Windows-x64.zip`: clean neutral installation / legacy core update.
- `3SHub-3SO-Windows-x64.zip`: 3SO edition.
- `3SHub-SeT-Update-Windows-x64.zip`: Se.T! update payload for the in-app updater.
- `update.json` and `SHA256SUMS.txt`: version, package sizes and SHA-256 hashes.

Legacy executable and ZIP names remain intentional compatibility identifiers. The visible application is 3SManager. Windows executables are currently **unsigned**; published SHA-256 hashes verify download integrity, not a code-signing certificate.

Historical release titles describe the product name at publication. No organizer credentials or private Se.T! data are included in release packages.
