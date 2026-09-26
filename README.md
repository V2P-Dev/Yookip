# Yookip

[Русская версия](README.ru.md)

A personal, offline-first desktop assistant for Windows 10 and 11.

Yookip replaces scattered text files with a fast library of response templates: find, prepare, and copy the right text in seconds without changing the saved original.

## Features

- **Response templates** — sections, labels, instant search across thousands of templates, one-click copy, and temporary edits that keep the original intact.
- **Reference** — permanent editing and TXT import.
- **Home** — today's schedule, a countdown to the next break, and optional weather, news, and fact cards.
- **Tasks and schedule** — a planner, work shifts (including overnight), and on-device recognition of schedules from images.
- **Reminders** — before breaks and before the end of the workday.
- **Graph** — a visual map of template relationships.
- **Tray and backups** — work from the tray; export and restore your data.

## Privacy

Everything works without the internet. Templates, searches, edits, tasks, and schedule images never leave your computer. Network cards are optional and can be turned off.

## Installation

1. Open the [latest release](https://github.com/V2P-Dev/Yookip/releases/latest).
2. Download `Yookip-<version>-Setup.exe` and run it. No administrator rights are required.

Updates arrive inside the app. The manifest signature and package SHA-256 are verified before installation, and a backup is created before any database change.

## Verifying downloads

Each release includes `SHA256SUMS.txt`, `release-manifest.json`, and its signature `release-manifest.json.sig`.

```powershell
Get-FileHash .\Yookip-0.2.0-Setup.exe -Algorithm SHA256
```

Compare the result with the matching line in `SHA256SUMS.txt`.

## Versioning

Yookip follows [Semantic Versioning](https://semver.org/): fixes increase the last number, new features increase the middle one. See [Releases](https://github.com/V2P-Dev/Yookip/releases) for the change history.

The source code is kept in a separate private repository; this repository publishes only installers, update packages, and their metadata.
