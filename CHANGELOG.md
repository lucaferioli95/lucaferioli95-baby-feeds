# Changelog

## 1.4.0 - 2026-11-20
- Alarm style (optional switch under the reminder): the notification is sent as high priority, vibrates in a long pattern and stays on screen until you tap it. A web app cannot ring like the phone's own alarm clock or get past Do Not Disturb, so the sound is the phone's notification sound.

## 1.3.0 - 2026-11-20
- Reminder: set the time of the next feed on a clock ("Next feed at"). A time that has already passed today means that time tomorrow, so it rolls over midnight. The "In 3 h" button is a quick reminder three hours from now.
- Without a picked time the reminder is still 3 h after the start of the latest feed. Starting a new feed clears a picked time. The hours box is gone.

## 1.2.1 - 2026-11-20
- New look: light cream background with a peachy rose palette (always light, no dark mode). New app icon to match.

## 1.2.0 - 2026-11-20
- Next-feed notification: a switch on the Live tab asks permission and then sends a normal notification (no alarm) a set number of hours after the start of the latest feed (3 h by default, changeable). It is sent by a small server job, so it arrives even when the app is closed. Editing, adding or deleting a feed moves the reminder. A Test button sends one straight away.
- On iPhone the app must be added to the Home Screen first for notifications to work.

## 1.1.0 - 2026-11-20
- Breast used: tap Left, Right or both on the Live tab (while feeding or when stopping) and on the Add / Edit tab. It shows next to the duration in History and as a Breast column in the CSV export.

## 1.0.0 - 2026-11-20
- First version. Live tab: Start / Stop a feed with a running timer, then add the top-up in ml. Add tab: record a feed after the fact (date, start, end, top-up). History tab: feeds grouped by day with daily totals, tap to edit or delete, export to CSV.
- Data is stored on the device only.
