# Skystrike 3D / Air Commando

Browser fighter-pilot game with procedural Web Audio, four weapons, ammo counters, wingmen, assisted runway landing, and ejection with on-foot combat.

Click **START MISSION**. Use WASD/arrows to fly, Space to fire, scroll or 1–4 to switch weapons, Shift for afterburner, E to eject, and R to restart. Sound and ejection also have onscreen buttons. Touch/coarse-pointer devices expose held direction, boost and fire buttons plus weapon cycling; after ejection, touch-drag on the open screen aims the sidearm.

## Source and hosting

`source/skystrike_3d.html` preserves the exact downloaded artifact. `index.html` changes only the Three.js import to the bundled `vendor/three.module.js` (0.160.0). Its license is retained in `vendor/THREE-LICENSE.txt`. Scenery and sound are generated in code; no separate media assets are required.

This update comes from the user-supplied attachment, locally renamed `air_commando_mobile.html`. The original attachment had a `.pdf` filename but contains UTF-8 HTML, not PDF bytes. The artifact title is **Air Commando — Fighter Pilot**. Its SHA256 is `4505f706978bf14b9f983a4f2804ce31c3f9351adf7c293db45fdb599491fdd9`. The source copy preserves the attachment bytes exactly.

This version adds swipe aiming during flight, pointer capture for held touch buttons, revised mobile placement, and hidden touch controls on mission end screens.

The checkout retains its existing Skystrike repository and Pages address. Local update preparation does not publish a release.
