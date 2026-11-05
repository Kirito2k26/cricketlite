# Cricket Lite

2D browser cricket with **Single Player vs AI** and **Local 1v1 (same computer)**.

## Run
Open `index.html` in a modern browser. No installation or server needed.

## Local 1v1
Choose **Local 1v1** from Game Mode, select two different teams, overs, then start. One player bats and the other bowls on the same screen; roles reverse for the second innings. The bowler selects a delivery and clicks **BOWL**, and the batter times **SWING** when the ball approaches. Use the on-screen controls to avoid keyboard contention. Both players share the screen, so this is not split-screen.

## Controls
Bat: shot direction and type, click SWING (or Space when ball is moving). Bowl: click pitch to aim, select delivery/power, click BOWL (or Space when no ball is active). Pause/Resume available.

## Notes
Online multiplayer and server code are not included. Fielding, running and some dismissal rules are simplified.


## Branding
`logo.png` is the Cricket Lite logo; `favicon.ico` and `favicon.png` are browser tab icons. `index.html` links to these files and displays the logo in the header.


## Balanced batting update
SWING during run-up queues a shot at the optimal contact point. Manual timing gives perfect, good, weak, or missed contact; timing windows scale with Easy/Medium/Hard. The batting panel shows a live timing indicator.
