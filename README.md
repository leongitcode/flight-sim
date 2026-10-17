# Low Pass

A light-plane flight simulator that runs in the browser. Take off from runway 36, fly a ring course over hills and sea, then land back on the strip.

**Play it:** https://leongitcode.github.io/flight-sim/

## The course

- Fly through all 10 rings in order. The next ring glows orange and a marker on screen points to it.
- After the last ring, land on the runway and come to a stop. Your total time is shown when you finish.
- Touchdown is rated by vertical speed: Butter, Smooth, Firm or Hard.
- Hit the ground too hard, clip a wing, nose in, or land in the water and the flight ends. Press `N` to restart.

## Controls

| Action | Keys |
| --- | --- |
| Pitch | `W` / `S` or up / down arrows (`S` pulls the nose up) |
| Roll | `A` / `D` or left / right arrows |
| Rudder | `Q` / `E` (also steers on the ground) |
| Throttle | `R` up, `F` down |
| Brake | `B` or `Space` |
| Camera | `C` chase or cockpit |
| Auto-level | `H` on or off |
| Light | `L` day or dusk |
| Sound | `M` on or off |
| Pause menu | `P` or `Esc` |
| Restart | `N` |

On phones and tablets, use the left pad to steer and the right slider for throttle. Buttons for brake, camera and pause sit beside the slider.

## Flying tips

- Take off at about 50 knots: hold throttle with `R`, then ease the nose up with `S`.
- Pulling up too hard at low speed causes a stall. Watch for the STALL warning and lower the nose.
- Auto-level brings the wings back to level when you let go of roll. Turn it off with `H` for full manual flight.
- The PULL UP warning means the ground is close on your current path.

## Run it locally

It is a single `index.html` file with no build step. Open it in a browser. It loads three.js and the fonts from a CDN, so it needs an internet connection and WebGL.

## Built with

[three.js](https://threejs.org/) for the 3D scene, plus plain JavaScript for the flight model and instruments.
