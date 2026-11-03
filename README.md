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
