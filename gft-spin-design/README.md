# GFT Spin Refresh: design files

Open `index.html` in a browser. It works offline. Press **Spin the wheel**: it really spins, but it uses demo odds.

**Kept from the current app:** the eight prizes in the same clockwise order (Tyres 4+1, $50 Fuel, 20% Brakes, Wipers, Wash & Wax, Safety check, Scan report, No luck) and 3 spins per week.
**Examples only:** prize descriptions marked "Confirm", use-by periods, codes and odds.

## assets/wheel
- `prize-wheel.svg`: the tyre-style wheel, 340 × 340, centred on 0,0 (viewBox -170 -170 340 340). Rotate everything except the "GFT" hub text. To land on prize *i* (0 = Tyres, clockwise), rotate to `360 − (i × 45 + 22.5)` plus 5 full turns, with up to ±15° of jitter.
- `wheel-pointer.svg`: red pin, placed at the top centre.

## assets/prize-icons (24 × 24, stroke = currentColor)
tyres, fuel, brakes, wipers, wash, safety, scan, noluck.

## assets/coupons
`ticket-*.svg`: prize tickets for the My prizes wallet (300 × 96). Code and use-by are example text. Render them from data in the app.

## assets/components
`spin-ticket-available.svg` and `spin-ticket-used.svg` for the 3-a-week counter.

## assets/backgrounds
The same six backgrounds as the other tabs.

## Before launch
- Decide results on the server, then animate the wheel to that result.
- Put official rules and odds in the app, including "Apple is not a sponsor" (App Store Review Guidelines 5.3). Check Google Play's contest policy too.
- Check Australian trade promotion lottery rules for each state customers may play from.
