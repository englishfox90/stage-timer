# Stage Timer

A big, colourful, slightly cheeky countdown for conference speakers. Put it on an iPad facing the stage and the speaker can read it from across the room.

- **Giant digits**, green → yellow → red → pulsing red in overtime, with a progress bar along the bottom
- **Last 10 seconds** turn into one huge bouncing number
- **Comedy mode** (on by default): a burrito spins past when it's time to wrap up, a plane flies through for "land the plane", confetti at zero, and the jokes get worse the longer they run over (the hook *will* come). Switch it off for a serious session and you just get plain messages.
- **Sound** (off by default): beeps at yellow and red, a sad trombone at zero, honks in overtime
- Works **offline** once loaded, keeps the screen awake, and picks up where it left off if the page reloads

## Using it

1. Open the site on the iPad in Safari → **Share → Add to Home Screen**. Launch it from the icon so it runs full screen with no browser bars.
2. Pick a duration (or type a custom one) and set when it turns yellow and red.
3. Tap **Start**. Tap anywhere to **pause**. From the pause screen you can do ±1 min, Reset, or Resume.

Keyboard (laptop): `Space` start/pause · `↑`/`↓` ±1 min · `R` reset (while paused) · `F` full screen.

**Preview all the gags quickly:** add `?speed=30` to the URL to run the clock 30× faster. Nothing gets saved in this mode.

## iPad checklist for the day

- Settings → Display & Brightness → **Auto-Lock: Never** (the app asks for a wake lock too, but belt and braces)
- Brightness up, Do Not Disturb on, plugged in
- Optional: **Guided Access** (Settings → Accessibility) stops anyone leaving the app by accident
- Open it once while you're online so it caches for offline use

## Deploying

Plain static files, no build step. Push to GitHub and enable Pages (Settings → Pages → deploy from `main`, root).
