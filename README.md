# PUP-PAD 🐾

A lightweight, landscape-first static web interface with six swipeable badge panels and interactive character previews. Built with HTML, CSS and vanilla JavaScript, without a backend or third-party scripts.

## Features

- Press the paw-shield home button to start at Chase. Two opening audio clips play in sequence.
- Swipe left or right through six badge panels in a continuous loop. Quick flicks can move across several panels; release snaps to a complete panel.
- Tap a badge for press feedback, a dark character overlay and that character's audio clip. Tap anywhere on the overlay to stop playback and return to the same badge.
- Responsive landscape layout, a repeatable background pattern, glow and vignette, and an orientation reminder.

## Files

- `index.html` — page layout, visual styles and interactions.
- `assets/home-paw-shield.png`, `assets/pattern-dog-bones.png` — home artwork and background pattern.
- `assets/badge-*.png` — earlier badge illustrations, retained as optional alternatives.
- `images/badge/` — badge images displayed by the current carousel.
- `images/characters/` — character portraits for the overlay.
- `audio/` — opening and character audio clips.
- `.nojekyll` — static GitHub Pages configuration.

## Run

Keep the directory structure intact. Open `index.html` in a modern desktop browser or serve the directory as a static website. On supported mobile browsers, use a user gesture to start audio and optionally add the hosted website to the home screen for a standalone landscape view.

A web app manifest and offline service worker are not included.

## Media and attribution

This fan-made interface includes original interface illustrations and third-party character-related visual and audio material. The presence of media files in this repository does not grant reuse or redistribution rights to third-party content. Character, artwork, trademark and recording rights remain with their respective owners. This project is not officially affiliated with the franchise or its rights holders.
