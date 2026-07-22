# Football English Interactive H5

A self-contained, static-hosting-ready 25-minute lesson based on `TL-football-2606.pptx`. Source pages 1 and 4, plus the previous speaking and reminder scenes, were intentionally removed. A supported Mini Commentary Challenge now appears after the position map, leaving 22 H5 scenes.

The vocabulary sequence preserves all 11 source items, one word per scene: player, goalkeeper, defender, midfielder, striker, winger, penalty, playmaker, offside, free kick, and sent off. Each word uses a local MP3 generated through the configured third-party speech API. All 11 fill-in-the-blank questions, the answer key, review, teacher notes, and the original CEFR image are retained. The final Mini Commentary Challenge asks learners to identify the striker and action, then say one complete sentence; a built-in hint guarantees a low-pressure finish.

All lesson artwork is newly generated project-local PNG imagery in one international football championship visual system. The package does not reuse the source deck's photographs, include SVG substitutes, or depend on third-party image URLs.

## Preview

Open `index.html` directly, or serve this folder with any static server.

## Configure

Edit `course.config.js`:

- `brandName`, `lessonTitle`, `level`, `durationMinutes`
- `accent` for the primary color
- `teacherHintLanguage`: `en` or `ar`
- `showBrand`, `soundOn`, `shareMode`

Runtime URL overrides are also supported:

- `?locale=en`
- `?teacherHints=ar`
- `?scene=8` opens a specific scene for QA or sharing

## Deploy

Upload the whole folder to the root of GitHub Pages, Vercel, Netlify, Cloudflare Pages, or any CDN/static host. No build command, account secret, API, or server is required.

## Controls

- On-screen previous/next controls
- Keyboard: Left/Right arrows to navigate, `T` for teacher notes, `R` to reveal/reset
- Responsive layout for desktop, tablet, and mobile
