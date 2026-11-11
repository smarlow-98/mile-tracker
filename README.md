# Mile Tracker for Android

A screen-reader friendly mileage tracker that measures miles with live GPS, like Virtual Cockpit on iPhone.

## Features
- Start and stop trips with one big button. Tracking keeps going with the screen off or the phone in your pocket (an ongoing notification has a Stop trip button).
- Live speed, trip distance, trip time, odometer, and GPS signal quality.
- Read status button speaks everything at once through TalkBack.
- Optional spoken announcement every mile (or kilometer), even with the screen off.
- Multiple vehicles. Switch between them from the Vehicle drop-down on the main screen.
- Add a vehicle by Year (1990 to next model year), Make and Model drop-downs. Built-in list of about 50 makes, and when online it pulls the complete model list for that year from the free US government (NHTSA) vehicle database. Choose "Other" to type anything not listed.
- Each vehicle keeps its own odometer. Enter the current reading when you add it, and trip miles are added automatically.
- Trip purpose (Personal, Business, Medical, Charity, Commute, Other).
- Trip history per vehicle with month, year, business, and all-time totals. Export all trips to a CSV spreadsheet and share it by email, Drive, etc.
- Miles or kilometers setting.
- If Android kills the app mid-trip, the trip is saved every 10 seconds and resumes when you reopen the app.

## Getting the APK
Open this repository's Releases page on your phone, download the newest MileTracker APK, and install it. Each push to main rebuilds it automatically.

The app source is in MileTracker.tar.xz; the build workflow unpacks and builds it. The signing key is kept in the repository secret SIGNING_KEY (never in the code), so every version installs over the last one without losing your data.

## First run
1. Add your first vehicle when asked.
2. Press Start trip. Allow location (choose Precise, While using the app) and notifications.
3. Press Stop trip when you arrive, either in the app or from the notification.

For best results, turn off battery optimization for Mile Tracker: Settings, Apps, Mile Tracker, Battery, Unrestricted.
