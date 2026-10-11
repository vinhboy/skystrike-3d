# Skystrike 3D / Air Commando

Browser fighter-pilot game with procedural Web Audio, four weapons, ammo counters, wingmen, assisted runway landing, and ejection with on-foot combat.

Click **START MISSION**. Use WASD/arrows to fly, Space to fire, scroll or 1–4 to switch weapons, Shift for afterburner, E to eject, and R to restart. Sound and ejection also have onscreen buttons. Touch/coarse-pointer devices expose held direction, boost and fire buttons plus weapon cycling; after ejection, touch-drag on the open screen aims the sidearm.

## Source and hosting

`source/skystrike_3d.html` preserves the exact downloaded artifact. `index.html` changes only the Three.js import to the bundled `vendor/three.module.js` (0.160.0). Its license is retained in `vendor/THREE-LICENSE.txt`. Scenery and sound are generated in code; no separate media assets are required.

This update comes from the final HTML artifact exposed by the supplied shared conversation, https://chatgpt.com/share/6acba71b-f82c-83e8-a1c5-b7e441bdf5c9 . The artifact title is **Air Commando — Fighter Pilot**. Its SHA256 is `b1a17e538bfaf2f781aa037decf4566a19af44445e34dc5f90524336cf16da40`. The shared page does not expose creation time or global version history.

The checkout retains its existing Skystrike repository and Pages address. Local update preparation does not publish a release.
