# MyMusic

A polished React/Vite music app starter with a Spotify/Apple-Music-inspired premium feel and an original interface.

## Run locally

1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev`.
4. Open the local URL shown by Vite.

## Connecting Google Drive

The UI currently uses demo artwork and a centralized player architecture. Google Drive should be connected through a secure backend/API layer rather than exposing credentials in the browser.

For production background playback on Android, package the app with Capacitor (or use React Native/another native audio layer) and use the platform's Media Session/background audio APIs.
