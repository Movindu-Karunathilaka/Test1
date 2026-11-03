# GFT Profile Refresh: design files

Open `index.html` in a browser. It works offline. The phone is clickable: tap the tiles, rows and back buttons to move between Profile, Personal details, My garage, Notifications, Notification settings and Contact.

**Kept from the current app:** Garage Full Throttle, 306 Hume Hwy, Craigieburn VIC 3064, (03) 9305 6198. Hours: Mon–Fri 8:30 am–5:30 pm, Sat 9:00 am–2:30 pm, Sun closed. Name, mobile and birthday fields.
**Examples only:** every customer name, number, birthday, car, plate and notification. The comparison screenshot has the email blurred.

## assets/avatars
`avatar-no-name.svg` (dashed, before a name is added), `avatar-tier-1/2/3.svg` (initials with the tier ring and badge).

## assets/icons (24 × 24, stroke = currentColor)
garage, bell, phone, gift, edit, settings, shield, doc, logout, trash, apple-id, cake, message, nav, copy, clock, search, camera, wrench, check, spin, star, alert, chev, back, plus, car, user, home, cal, cardb.

## assets/illustrations
- `empty-garage.svg`: My garage empty state
- `map-schematic.svg`: placeholder only. Use a real map in the app.

## assets/components
`status-open.svg` and `status-closed.svg`.

## Open/closed logic (used in index.html)
Hours in minutes since midnight, Melbourne time (Australia/Melbourne): Mon–Fri 510–1050, Sat 540–870, Sun closed.
- Open: "Open now · closes 5:30 pm".
- Before opening: "Closed · opens today 9 am".
- Otherwise: "Closed · opens tomorrow/Mon 8:30 am".

## Before launch
- Delete account in the app (App Store Review Guidelines 5.1.1; Google Play has a similar rule).
- Register the sending email domain with Apple's private email relay, or emails to hidden addresses won't arrive.
- The privacy policy should explain why birthday and mobile are collected.
- Keep marketing notifications opt-in and separate from job updates.
