# GFT Points History Refresh: design files

Open `index.html` in a browser. It works offline. Tap any entry in the phone to open its detail sheet, and try the filter chips.

**From the current app (this account):** 520 pts = +500 (Appointment APT-000008, $1,000, 7 Nov 2026) + 20 sign-up bonus (1 Nov 2026). Member rate 5 pts per $10; non-member 1 pt per $100; Tier 2 at 1,000, Tier 3 at 2,750.
**Examples only:** the busy Tier 2 member and the non-member views (service names, cars, references, amounts).

## Maths used in the mockup
- Member points = floor(paid / 10) × 5. Non-member points = floor(paid / 100).
- Dollars to the next tier = points needed × 2. For example, 480 pts → $960.
- The garage should confirm rounding, whether points use the amount before or after the discount, and whether GST counts.

## assets/entry-icons
`entry-job`, `entry-bonus`, `entry-tier`, `entry-referral`, `entry-adjustment` (38 × 38 tiles in each type's colour).

## assets/components
- `points-coin.svg`
- `tier-progress-520-of-1000.svg`: the progress bar at this account's real numbers

## assets/icons (24 × 24, stroke = currentColor)
back, info, wrench, gift, star, user, edit, home, cal, cardb, spin.

## Colours
Earned `#5FE08F` (green, not red) · Taken back `#FF8A8E` · Tier milestone `#E6E9EE` / `#C9CDD3` · Brand red `#E0242B`.

## assets/backgrounds
The same six backgrounds as the other proposals.
