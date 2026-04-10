# obsidian-clipper-custom-builds

Self-hosted Firefox extension auto-update endpoint for personal obsidian-clipper customizations.

- `updates.json` — Firefox update manifest, polled automatically by installed extensions
- XPIs are published as GitHub Releases

The extension (installed from a release XPI) checks `updates.json` periodically and auto-updates when a new version is published.
