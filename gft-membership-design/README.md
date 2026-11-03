# GFT Membership Refresh: design files

Open `index.html` in a browser. It works offline.

**Kept from the current app:** Tier 1 under 1,000 pts (10% off), Tier 2 1,000+ pts (15%), Tier 3 2,750+ pts (20%), non-members 1 pt per $100, members 5 pts per $10, $19/month (was $29), and the three day-one perks.
**Examples only:** names, member numbers, savings, payment details, and the Tier 2 and 3 extras marked "Suggested".

## assets/cards (340 × 214)
`club-card-not-member.svg`, `club-card-tier-1.svg` (red), `club-card-tier-2.svg` (silver), `club-card-tier-3.svg` (gold on black). In the app, render the name, member number and points from data. These files show the layout.

## assets/perk-icons (40 × 40, stroke = currentColor)
percent-off, wiper-blade, headlight-polish, tyre-rotation, priority-booking, pickup-dropoff, safety-check, everything-below, locked.

## assets/components
- `tier-badge-1/2/3.svg`: hexagon tier badges
- `tier-track-example-*.svg`: progress track drawn to scale (0 / 1,000 / 2,750, scale ends at 3,500)

## assets/icons (24 × 24)
qr-code, wallet, lock, membership-card.

## assets/backgrounds
The same six backgrounds as Home and Appointments.

## Maths used in the mockup
- Member points = floor(job $ / 10) × 5. Non-member points = floor(job $ / 100).
- Tier 1 saving = 10% of the job.
- Dollars to the next tier (member) = points needed ÷ 0.5. For example, 360 pts → $720.

## Tier colours
Tier 1 `#E0242B` · Tier 2 `#C9CDD3` · Tier 3 `#D4A84A`
