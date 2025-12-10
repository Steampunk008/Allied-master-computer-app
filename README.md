# AM — Steampunk Chat (Firestore)

Simple chat web app (steampunk theme) using Firebase Firestore + Storage + Auth.

## Setup

1. In Firebase console create a project and add a **Web app**.
2. Enable **Authentication → Anonymous** or other providers.
3. Create **Firestore** and **Storage**.
4. Paste your firebase config into `js/firebase-config.js` (already included if you used the config I have).
5. Deploy as static site (GitHub Pages or Firebase Hosting) or run locally.

## Files
- `index.html` — main UI
- `css/steampunk.css` — theme
- `js/firebase-config.js` — your firebase config
- `js/app.js` — app logic (chat, groups)
