# Miguel Luner Clock Studio

A responsive clock and time-management web app built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Live digital and analog clock faces with multiple visual styles
- 12/24-hour format, date, timezone and day-progress display
- Create, edit, enable/disable and delete alarms
- One-time and weekday-repeat alarms; three synthesized alarm tones
- Five-minute snooze and dismiss controls
- Stopwatch with lap timing
- Countdown timer with quick presets
- World clock with selectable cities
- Dark mode, fullscreen mode and responsive mobile layout
- LocalStorage persistence for alarms and display preferences

## Run
Open `public/index.html` in a modern browser, or open the project folder in a code editor such as VS Code and use a local static server.

No backend or installation is required.

## Important alarm limitation
Browser-based alarms can only sound while the page is open and the browser/device allows JavaScript and audio to run. Browsers may suspend tabs, and alarms cannot be guaranteed after the browser is closed or the device sleeps. For reliable background alarms, this would need a native mobile app or a server/push-notification architecture. Browser audio may require a user interaction before playback. Notification permission is optional and requested after interacting with the alarm form.

## Storage
Alarms and preferences are stored in the current browser's LocalStorage. Clearing browser site data will clear those saved settings. Data does not automatically sync between devices.
