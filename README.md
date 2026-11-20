# Daily Task Tracker

A lightweight, private daily checklist for 11 scheduled tasks. Progress stays in your browser unless you export or transfer it.

## Features

- Daily, weekly, and monthly completion and missed-task stats
- Editable task start times and durations, with expired tasks locked
- Automatic month creation and a live slot timer
- Light, dark, and system themes
- JSON backup and restore, plus QR transfer between devices
- Compact, scrollable table with a Go to today control

## Use

Open `index.html` in a modern browser. Data is stored locally in that browser. To move it to another device, use **More actions → Send via QR** and **Receive via QR**, or export and import a JSON backup. Camera scanning requires browser camera permission and a secure page such as HTTPS or localhost.

## Deploy

This is a static site. Serve the repository root with any static web host. Use HTTPS to enable camera based QR scanning on phones.

## Privacy

The tracker has no account or server connection. Your checklist and settings remain in local browser storage until you export or scan a transfer code.
