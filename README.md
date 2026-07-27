# Nova Weight Tracker

A simple Nova-branded weight tracker for Lewis and Ben.

## Features

- Starting weights entered in stone and pounds
- Official Monday weigh-ins
- Optional additional weigh-ins on any day
- Visual progress line graph
- Individual progress summaries and milestone badges
- Nova dark theme with embedded branding

## Local preview

```bash
npm install
npm run serve
```

## Firebase Hosting

The app is configured for Firebase Hosting through `firebase.json`.

```bash
npm install
npx firebase login
npx firebase use --add
npm run deploy
```

The current version stores weigh-ins in the browser's local storage. Firebase
Hosting makes the tracker available online, but entries do not yet sync between
different devices.
