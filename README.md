# 🔔 NoteAlarm - Android Notes + Alarm App

A fully local PWA (Progressive Web App) you can install on Android WITHOUT the Play Store.

## Files
- `index.html` — The full app
- `manifest.json` — Makes it installable as an Android app
- `sw.js` — Makes it work offline

## How to Install on Your Android Phone

### Option A: Use a local server on your PC (Recommended)
1. Put all 3 files in a folder
2. Install Node.js, then run: `npx serve .`
3. It will show a URL like `http://192.168.1.x:3000`
4. Open that URL in Chrome on your Android phone
5. Chrome will show a banner or you can tap ⋮ → "Add to Home screen"
6. Done! The app icon appears on your home screen.

### Option B: Use GitHub Pages (free hosting, no Play Store)
1. Create a free GitHub account
2. Upload these 3 files to a new repository
3. Go to Settings → Pages → Enable GitHub Pages
4. Open the Pages URL in Chrome on Android and install

### Option C: Android Studio / ADB
- Put the files in a local web server and use ADB to install a WebView wrapper

## Features
- ✅ Add notes/tasks for any date (defaults to tomorrow)
- ✅ Set alarm time per note — fires a notification + sound + vibration
- ✅ "Tomorrow" tab shows all reminders for tomorrow
- ✅ Mark notes done, delete notes
- ✅ Works fully offline after first load
- ✅ Data saved locally on your phone (localStorage)
- ✅ Test alarm button in Settings

## Permissions Needed
- **Notifications** — for alarm pop-ups (tap Allow in Settings tab)
