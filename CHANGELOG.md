# Changelog

## 2.1.0 - 2026-11-21
- History: each day is a drop-down with a one-line summary (feeds, minutes, top-up). Today is open by default and the other days are closed. Days you open or close stay that way while the list refreshes.

## 2.0.1 - 2026-11-21
- Top-up accepts one decimal digit (for example 2.5 ml). The quick buttons are now 1 and 3 ml. Totals and the CSV show one decimal where needed.

## 2.0.0 - 2026-11-21
- Shared history: sign in with Google (same allow-list as the Family Planner, so only you and Alice) and both phones see the same feeds. It still works offline and syncs when back online. Edits and deletes sync too. Feeds already on a phone are added to the shared history the first time it signs in.
- Reminders follow the shared history: a feed logged on either phone moves the reminder on both phones.
- Live tab: Start feed stays big in the middle, with a new Overview underneath: feeds, time at the breast, top-up, average and longest gap, which side to start on next, and a typical day. Switch between Today and the last 24 h.
- Removed the alarm style and the fake call; normal notifications only.

## 1.5.0 - 2026-11-20
- Ring like a call (optional switch under the reminder): when the reminder comes due and the app is open on screen, a full-screen incoming-call page appears with a looping ring tone and vibration. Answer starts a feed, the red button dismisses it. It also rings when you open the app from the notification within 10 minutes of the due time. The screen is kept on while the app is open and the switch is on.
- Limit: a web page cannot ring in the background or with the screen off; the notification covers that case.

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
