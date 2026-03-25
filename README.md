# :ninja: Ninja Hands

Catch flying fruit with your actual hands through the webcam. Close your fist to grab. Dodge bombs. Two hands for double the chaos.

## [Play Now](https://ashleywolf.github.io/ninja-hands/) (Chrome/Edge)

## What Is This

Fruit Ninja, but with your real hands. MediaPipe tracks 21 3D landmarks on each hand and detects grab gestures by measuring fingertip-to-palm distance. Fruit arcs across the screen, you close your fist to catch it, and bombs fly in to keep you honest. Two-hand support means you can dual-wield.

## Features

- 21 3D keypoints per hand, 2 hands tracked simultaneously
- Grab detection via fingertip-to-palm distance (close fist = grab, open = release)
- Big 80px fruit with radial glow (white/gold/red depending on point value)
- Darkened webcam background so you can actually see the fruit
- Frenzy mode every 45 seconds where fruit floods the screen
- Bomb smoke trails and screen shake when one detonates near you
- Near-miss "ALMOST!" feedback when you just barely whiff
- Hand glow aura at combo 10+ that goes rainbow at 20+
- Ambient pulsing audio that intensifies with combo count
- localStorage high scores

## How to Play

- Hold your hands up in front of the webcam.
- Fruit flies across the screen. Close your fist when your hand overlaps a fruit to catch it.
- Avoid bombs. If you grab one, it costs you.
- Build combos for bonus multipliers. Hit frenzy mode to rack up points fast.
- Stars give bonus points and a brief slow-mo window.

## Tech

- MediaPipe HandLandmarker tracking 21 3D keypoints per hand (up to 2 hands)
- Grab gesture detection via fingertip-to-palm Euclidean distance
- Real-time hand position mapped to canvas coordinates
- HTML5 Canvas with webcam overlay, CDN-loaded

## Browser Support

Chrome or Edge recommended. Requires webcam access. Works best with good lighting and a clear background behind your hands.

## Part of Browser Party Games

8 single-file browser games built with MediaPipe, Transformers.js, Web Audio, and Web Speech. No servers, no build steps, no installs.

| Game | Input | Tech |
|------|-------|------|
| [Type or Die](https://ashleywolf.github.io/type-or-die/) | Keyboard | Vanilla JS |
| [Grin Sweeper](https://ashleywolf.github.io/grin-sweeper/) | Smile (webcam) | MediaPipe Face |
| [Show & Tell](https://ashleywolf.github.io/show-and-tell/) | Real objects (webcam) | Transformers.js DETR |
| [Pitch Climber](https://ashleywolf.github.io/pitch-climber/) | Voice pitch (mic) | Web Audio API |
| [Spell Caster](https://ashleywolf.github.io/spell-caster/) | Shout spells (mic) | Web Speech API |
| [Stone Face](https://ashleywolf.github.io/stone-face/) | Don't react (webcam) | MediaPipe Face |
| [Ninja Hands](https://ashleywolf.github.io/ninja-hands/) | Hand tracking (webcam) | MediaPipe Hands |
| [Duck & Cover](https://ashleywolf.github.io/duck-and-cover/) | Duck + yell (webcam+mic) | MediaPipe Pose + Web Audio |

---
Built with vanilla JS + browser ML. Each game is one HTML file. Fork it, break it, make it yours.
