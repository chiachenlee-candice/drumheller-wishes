# Drumheller Wishes

Mobile web AR prototype: scan the QR code at Drumheller Fountain, design a virtual coin, attach a wish, and swipe up to toss it into the fountain. Browse your coins and other visitors' coins in a polaroid-style collection.

- Camera-first: the rear camera shows the real fountain; drag the ring onto the basin and pinch to resize it.
- Falls back to an illustrated fountain if the camera is unavailable or declined.
- In this hosted version, coins are saved on each phone only (localStorage). Coins marked "Example" are samples.

Live: https://chiachenlee-candice.github.io/drumheller-wishes/

## Versions

- **High-fidelity AR prototype** (git tag `v1-hifi`): https://chiachenlee-candice.github.io/drumheller-wishes/
- **Lo-fi wireframe for usability testing** (`lofi/`): https://chiachenlee-candice.github.io/drumheller-wishes/lofi/
  Black-and-white line drawings only. Flow: line-art fountain landing (with a Map of other locations) → sign or draw on the coin → write a wish under the coin → the camera turns on only for the swipe-up toss, with a splash → a Your coin / All coins popup where any coin opens to show its drawing and wish. Add `?nocam` to the URL to skip the camera.
