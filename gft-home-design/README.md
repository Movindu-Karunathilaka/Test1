# GFT Home Refresh: design files

Open `index.html` in a browser. It works offline. Everything in the mockup is example data.

## assets/backgrounds (375 × 812 SVG)
| File | Option |
|---|---|
| `bg-carbon-taillight.svg` | Carbon fibre + red tail-light glow (recommended) |
| `bg-taillight-glow.svg` | Red glow only |
| `bg-tyre-tread.svg` | Chevron tyre tread on both edges |
| `bg-contour-lines.svg` | Topographic lines (closest to LMCT+) |
| `bg-speed-lines.svg` | Diagonal light streaks |
| `bg-plain.svg` | Today's flat black |
| `pattern-tyre-tread-tile.svg` | 56 × 36 repeat tile for the tread pattern |

How to use: place the background at the top of each tab's scroll view, at full width, over a solid `#0B0B0D`, and let it scroll with the content. Each file fades to solid black at the bottom, so longer screens need nothing extra. Keep cards solid (`#18181B`) so text contrast doesn't change.

## assets/icons (24 × 24, stroke = currentColor)
Separate files plus `sprite.svg` (symbols `i-<name>`). Set the colour from your code, e.g. `#FFFFFF` for normal icons and `#E0242B` for active ones.

## assets/components
- `points-coin.svg`: header points chip icon
- `tacho-dial-example-*.svg`: points progress dial at two example values. In the app, draw it from code; the geometry is in `index.html` (`drawDial`): a 270° arc, red zone in the last 15%, 11 ticks.
- `number-plate-vic.svg`: Victorian-style plate (example number)
- `badge-*.svg` / `badge-*-locked.svg`: achievement badges
- `wordmark-placeholder.svg`: placeholder only. Replace it with GFT's real logo.

Text in the SVGs uses Barlow / Barlow Condensed (Google Fonts), with Arial as the fallback. Outline the text in Figma or Illustrator if you need exact lettering.

## Colours
Black `#0B0B0D` · Card `#18181B` · Border `#2A2A31` · Red `#E0242B` · Red text on dark `#FF4A50` · Created `#F5A524` · Approved `#4C8DF6` · Ready `#2DC66B`

## assets/images
`hero-neon-car.jpg` (cropped from the current app) and `current-home.jpg` (screenshot of today's Home, for comparison). These are photos, so they stay as JPG.
