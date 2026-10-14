# PULSE BREAKER — browser edition

Neon arena action, built from the original Python/pygame game using pygbag 0.9.3.

## Play

Choose Festival (60 seconds) or Endless Survival on the home page.
Use a PC with a keyboard and mouse. Arrow keys move, mouse aims, left click fires or charges the acquired laser, Shift dashes, right click/E reflects, Escape pauses.
Click the game frame once to enable sound. The first load downloads the Python WASM runtime from pygame-web's CDN.
Scores and preferences are stored locally in this browser, separately for each mode. Existing PC records are not uploaded. There is no shared server leaderboard.

## Render static-site settings

- Branch: main
- Build command: `echo "Static browser build ready"`
- Publish directory: `.`
- `render.yaml` is also provided for Blueprint deployments.

The prebuilt `game.tar.gz` contains the Python source, nickname filter and bundled fonts including their license notices.
The original desktop installation is maintained separately.
