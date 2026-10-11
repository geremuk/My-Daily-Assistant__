# My Daily Assistant — Android PWA

## Included
- Daily dashboard, task manager, priorities, due dates, and task reminders
- Calendar-style upcoming events and deadlines
- Daily routines and morning/evening check-ins
- Local browser storage and JSON export
- Web app manifest and service worker for installability/offline shell

## Install on Android
A PWA must be served from an HTTPS website (or localhost for testing). This ZIP is not already hosted.
1. Upload the contents of this folder to an HTTPS static host such as GitHub Pages, Netlify, or another web host.
2. Open the deployed URL in Chrome on Android.
3. Use Chrome's menu (⋮) → Install app / Add to Home screen.

## Important limitations
- This chat created the app source package, but did not publish it to a website or install it on your phone.
- Tasks/events/check-ins are saved in this browser's local storage on this device; they do not sync between phone and computer. Export data in Settings to back it up.
- Browser notifications depend on browser/device support and permission. Task reminder checks happen while the app page is open; this app cannot guarantee alarms/notifications when fully closed or the device is asleep.
- For a dependable 6:00 AM wake-up alarm, set a recurring alarm in Android Clock. Use a separate bedtime reminder for 10:30 PM and aim for 11:00 PM bedtime.
- Time zone intent is Africa/Addis_Ababa. Dates/times use the device's local time; keep the device set to East Africa Time (UTC+3).
