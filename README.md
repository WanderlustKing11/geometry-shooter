# geometry-shooter
HTML5 Canvas Game, circle on circle violence

- Player shoots projectiles from center of the browser.
- New enemies spawn every second randomly from out of screen, in various sizes, and are pulled towards the center screen.
- Accurate collision detection between sprites (player, enemies, and projectiles).
- Dynamic scoring: Shrinking an enemy is 100 pts, 250 for eliminating them.
- Score tally at the top of screen.
- Game-Over UI shows end score and restarts the game.
- Garbage collection details, remove the rogue projectiles that go off screen to avoid unnecessary computation and maintain fast performance.
- Environment and sprites drawn with Canvas, and smooth animations created with GSAP.

I really enjoyed playing Geometry Wars. I would like to continue this project in that direction by creating varying enemy behaviors, adding mobility to our player, and throwing some powerups in there, too.

As always, feel free to use this however you'd like. Have fun!
