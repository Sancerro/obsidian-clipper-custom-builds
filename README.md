# relege-builds

Self-hosted Firefox auto-update endpoint for **Relege** — a private, durable reader that saves, highlights, and syncs web pages, PDFs, and EPUBs.

- `updates.json` — Firefox update manifest, polled automatically by installed builds
- Signed XPIs are published as GitHub Releases

Installed Relege builds check `updates.json` periodically and auto-update when a new version is published.