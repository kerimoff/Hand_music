# Hand Music

A phone-first air harp. Your front camera tracks your index fingertip, and swiping it up or down through the strings on screen plays them.

**Play:** https://kerimoff.github.io/Hand_music/ (once GitHub Pages is on for this repo)

- **Key**, **Scale**, **Sound**: tap to cycle.
- No camera? Choose "Play with touch only" and swipe on the screen.
- Everything is one `index.html`. Sound is synthesized with Web Audio; hand tracking is [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) (Apache-2.0), loaded from a CDN.

Inspired by [Hashem Al-Ghaili's Music Maker](https://github.com/Hashem-Al-Ghaili/music-maker). No code was copied from it (it has no license); this is a separate, much smaller rewrite.
