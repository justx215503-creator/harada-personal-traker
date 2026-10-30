# Harada Personal Development Tracker

A mobile-first, installable web app (PWA) for your Harada development plan.

## Included
- Editable main goal
- Daily 60-minute routine (15 + 20 + 15 + 10 minutes)
- Learning journal
- 8 development areas / 64 actions
- Weekly review prompts
- 12-month roadmap
- Automatic local saving in the browser
- Offline caching after first successful load

## Important
The tracker stores data in the browser's local storage on the device. It does not sync between devices. Clearing browser/site data may erase your tracker data, so periodically export/backup is not currently built in.

## Install on Android
1. Publish these files to a static HTTPS host (for example, GitHub Pages or Netlify).
2. Open the published HTTPS link in Chrome on your Android phone.
3. Open Chrome's menu (three dots) and choose **Install app** or **Add to Home screen**.
4. Confirm. The tracker will open like an app from your home screen.

A PWA needs an HTTPS website (or localhost for development) for service-worker/offline installation. Opening the HTML file directly from a file manager does not provide the full installable/offline experience.

## Preview locally
Open `index.html` in a browser. The tracker interface works, but service-worker installation requires HTTPS or localhost.
