# Beachstorm — Shoreline Defense

An original browser arcade game in the spirit of the classic beach-assault
turret shooters: you man the last 360° gun emplacement on an island while
waves of landing craft, infantry, tanks and helicopters storm the shore.

**Play it:** open `index.html` in any modern browser. Everything is in that
one file — no build step, no dependencies, no network access needed. All
graphics are drawn on canvas and all sound is synthesized with WebAudio.

## Controls

| Input | Action |
| --- | --- |
| Mouse | Aim the crosshair |
| Screen edges · `A`/`D` · arrow keys · mouse wheel | Swing the turret (full 360°) |
| Hold left mouse button | Machine gun (watch the heat gauge) |
| Right mouse button / `Space` | Cannon shell — area blast, kills armor |
| `R` | Reload shells |
| `P` / `Esc` | Pause |
| `M` | Mute |

Touch is supported: drag to aim, and use the on-screen FIRE / SHELL buttons.

## How it plays

- Enemies come from **every bearing** — watch the radar (top right) and the
  red edge chevrons for flanking contacts.
- Landing craft drop squads of infantry at the waterline; sink a boat before
  the ramp opens and the whole crew goes down with it (bonus points).
- Tanks are machine-gun-proof — two well-aimed cannon shells put them down.
- Helicopters orbit and fire rockets; a direct cannon hit drops them instantly.
- Each cleared wave patches your hull (+15) and shifts the time of day:
  dawn → day → dusk → night. At night, your searchlight follows the crosshair.
- Your best score is kept locally in the browser.
