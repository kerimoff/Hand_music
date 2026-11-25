# Hand Music

An air harp for your phone. Stand the phone up so the front camera sees both hands, then:

- **Make a string:** with one hand, pinch thumb and index and hold still until the ring fills (half a second), then drag and let go. Quick accidental pinches are ignored. The string runs from where you pinched to where you let go.
- **Play:** sweep your index fingertip through a string (either hand).
- **Key / Scale / Sound:** tap to cycle. Notes are shown as Do Re Mi Fa Sol La Si. Sounds: guitar, piano, harp.
- **Clear** removes all strings. The camera mode starts with none; draw your own. A string is cancelled if your hand leaves the view while drawing it.
- No camera? "Play with touch only" and swipe on the screen.

**Play:** https://kerimoff.github.io/Hand_music/

Everything is one `index.html`.

## Credits

- Hand tracking: [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) (Apache-2.0), loaded from a CDN.
- Instrument samples: FluidR3 GM soundfont by Frank Wen, as converted in [gleitz/midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Loaded per note on demand.
- Inspired by [Hashem Al-Ghaili's Music Maker](https://github.com/Hashem-Al-Ghaili/music-maker). No code was copied from it (it has no license); this is a separate, much smaller rewrite.
