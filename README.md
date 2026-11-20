# Drumheller Wishes

Mobile web AR prototype: scan the QR code at Drumheller Fountain, design a virtual coin, attach a wish, and swipe up to toss it into the fountain. Browse your coins and other visitors' coins in a polaroid-style collection.

- Camera-first: the rear camera shows the real fountain; drag the ring onto the basin and pinch to resize it.
- Falls back to an illustrated fountain if the camera is unavailable or declined.
- In this hosted version, coins are saved on each phone only (localStorage). Coins marked "Example" are samples.

Live: https://chiachenlee-candice.github.io/drumheller-wishes/

## Versions

- **High-fidelity AR prototype** (git tag `v1-hifi`): https://chiachenlee-candice.github.io/drumheller-wishes/
- **Lo-fi wireframe for usability testing** (`lofi/`): https://chiachenlee-candice.github.io/drumheller-wishes/lofi/
  Grayscale boxes only. It keeps the live camera and the real swipe-up gesture, which paper can't simulate, and tests three tasks: sign or draw on a coin with your finger and write a wish, toss it, and find another visitor's wish. Add `?nocam` to the URL to use the placeholder instead of the camera.
