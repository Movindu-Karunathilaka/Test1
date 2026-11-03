# GFT Appointments Refresh: design files

Open `index.html` in a browser. It works offline. Everything in the mockup is example data: names, plates, prices, times and services.

The page has the phone mockup (three customer states, Upcoming / History, working Approve / Call me buttons), the five job statuses with push notification copy, the 3-step booking sheet, fixes to today's tab and a build order.

## assets/backgrounds
The same six 375 × 812 backgrounds as the Home refresh, so every tab matches. Place one at the top of the scroll view over a solid `#0B0B0D`.

## assets/icons (24 × 24, stroke = currentColor)
calendar, calendar-plus, map-pin, clock, receipt, search, book-again, alert, reschedule, phone, check, plus, wrench, car, camera, download, plus `sprite.svg` (symbols `i-<name>`).

## assets/components
- `status-*.svg`: status pills. Created (amber), Approved (blue), In progress (red), **Ready to pick up (green, a change from today's red)**, Completed (grey)
- `timeline-dot-*.svg`: dots for the live job timeline
- `date-tile-example.svg`: calendar date tile for booking cards
- `mini-plate-vic.svg`: small Victorian-style plate (example number)
- `app-icon-notification.svg`: placeholder app icon used in the notification mockups

## assets/illustrations
- `empty-first-booking.svg`: car on a hoist, for the first-booking empty state
- `photo-placeholder-*.svg`: stand-ins for real workshop photos (brake pad, tyre tread, air filter). In the app, these are photos the mechanic uploads.

## Colours
Black `#0B0B0D` · Card `#18181B` · Border `#2A2A31` · Red `#E0242B` · Created `#F5A524` · Approved `#4C8DF6` · In progress `#E0242B` · Ready `#2DC66B` · Completed `#8A8A93`

Text in the SVGs uses Barlow Condensed or the system font, with Arial as the fallback. Outline the text in Figma or Illustrator if you need exact lettering.
