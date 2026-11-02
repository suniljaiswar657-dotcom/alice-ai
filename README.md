# ALICE AI

A lightweight, mobile-first personal assistant starter built for Android devices, including Redmi 9 / Android 10.

## Current build
- Responsive mobile interface
- Installable PWA foundation
- Local task list stored in the browser
- Optional browser speech input
- Offline cache after the first successful load

## Honest capability status
This starter does **not** yet connect to a live AI model. Chat currently displays a clear setup notice rather than pretending to provide AI responses. No API key is required for the starter shell.

## Run locally
Serve this folder over HTTP (service workers require HTTPS or localhost). Open `index.html` in a modern browser for basic UI testing.

## Next milestones
1. Publish over HTTPS and verify installation on Redmi 9.
2. Connect a free-tier AI provider through a server-side endpoint; never expose provider keys in browser code.
3. Add secure user accounts and synced memory.
4. Add reminders and permission-based integrations.
5. Package an Android APK after testing.

Free AI services and hosting may have quotas or change their terms.