# Sip — Hydration companion

A responsive hydration app with an avatar reminder every 30 minutes, water logging, daily goals, history, and optional browser notifications. Preferences and today's log are saved locally in your browser.

## Develop

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

Keep the app open to receive reminders. Browser timers can be delayed in background tabs or while your device sleeps. Browser notifications require permission and HTTPS (or localhost). A web app cannot force a custom avatar to appear over other applications; the avatar appears inside the app, and permitted system notifications can appear outside it. No reminders run after the app is closed.

Use the play button beside “I drank water” to preview the avatar reminder. Log a glass, snooze for five minutes, or pause reminders. Daily totals reset at local midnight. No backend or account is required.
