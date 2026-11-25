# ilmi seed media

Images and video used by the ilmi `content` seed data (dev and staging) until the real CDN is
configured. Served through jsDelivr:

`https://cdn.jsdelivr.net/gh/yakhairy/ilmi-seed-media@v6/<folder>/<file>`

## v6 — Explore ilmi (UC18)
`explore/` holds the Explore seed: `mobile/` (Explore main hero and category art), `activities/`
(card arts and detail photos), `sessions/`, `locations/`, `presenters/`, `outcomes/` (SVG icons),
`spaces/`, `exhibitions/`, `learning/` (card pictures) and `learning/video/` (mp4), `web/`
(page banners). Every file is the Figma original or the Figma node exported at scale 1; the
file-by-file source table lives in the plan package (`Plans_Specs/explore-ilmi/seed-media.md`).

## v10 — Explore web tile icons (calendar C24)
`explore/category-icons/<key>.svg` for the keys `events` (ticket), `activities` (puzzle),
`galleries-and-gardens` (gallery) and `learning-resources` (learning): the Figma tile icons of the
Explore home frame (`wpMHFwV1gK6Th6HGqWN0uR`, node `284:33738`), 26 × 26, one navy fill. Only
`svg`, `g` and `path` elements: no script, no event handler, no style, no external reference.

## v11 — Explore mobile main page art, higher resolution
`explore/mobile/` `hero-whats-on`, `category-events`, `category-activities`, `category-spaces` and
`category-learning` replaced with the enhanced exports (about 3× the v10 size, which showed
pixelated on mobile). Same names, WebP quality 85, metadata stripped, transparency kept. Every other
file is unchanged from v10, so every older URL stays valid.

## v12 — every picture re-exported at 1920 × 1280
All 162 WebP pictures replaced with the UX team's high-quality exports, 1920 × 1280, same names and
folders. Six of them are then replaced with the newer content exports, same names:
`explore/web/banner-exhibitions` (375 × 405), `menu/menu-visit-ilmi-center` (308 × 224),
`menu/menu-events` (620 × 360, the Explore submenu art: leopard and robot), and the learning cards
`explore/learning/how-do-bats-see-in-the-dark`, `why-does-lightning-flash` and
`how-does-a-sundial-tell-time-with-the-sun` (1000 × 1778). The SVGs and videos are unchanged.
The tag stays under jsDelivr's 50 MB package limit (about 45 MB); a version above it answers 403.
Every older URL stays valid.

## v13 — mobile FAQ card with a transparent background
`mobile/discover_faq` replaced with a new 1920 × 1280 export with a transparent background (the v12
picture was opaque). Every other file is unchanged from v12, so every older URL stays valid.

## v14 — flat learning cards
Seven `explore/learning` cards replaced with new flat-style exports, same paths:
`how-do-bats-see-in-the-dark`, `how-do-birds-know-where-to-go` (564 × 1002),
`how-do-chameleons-change-color`, `how-does-a-sundial-tell-time-with-the-sun`,
`why-are-all-fingerprints-unique`, `why-do-cats-always-land-on-their-feet` and
`why-does-lightning-flash` (1000 × 1778). Every other file is unchanged from v13, so every older URL
stays valid.

## v15 — new Explore space pictures
Seven `explore/spaces` pictures replaced with new 1536 × 1024 exports, same paths: `alardh-garden`,
`journey-of-inventions`, `life-on-earth`, `live-lab`, `our-bodies`, `our-powers` and
`wonders-of-energy`. Every other file is unchanged from v14, so every older URL stays valid.

## v16 — Home "For schools" section
`home/for-schools.webp` (952 × 640, rounded corners on the section navy, as exported): the Figma S00 "Schools offering" picture
(`wpMHFwV1gK6Th6HGqWN0uR`, node `1172:15087`, the 476 × 320 "event thumb") exported at scale 2,
WebP quality 85, metadata stripped. Every other file is unchanged from v15, so every older URL stays
valid.
