Bug Fixes (Original Version)
.Fixed the left arrow key not responding by adding support for "ArrowLeft" in addition to "Left".
.Fixed a collision detection bug where the ball would pass through bricks without breaking them or increasing the score.
.Centered the brick layout by adjusting the horizontal offset and removing the extra spacing on the right side.
.Fixed the lives counter so it updates correctly on the screen.
.Adjusted the ball's initial spawn position to start slightly above the paddle for better gameplay


additions that i made
-Reworked the brick  collision system. This prevents the ball from passing through multiple bricks in a single frame and produces more accurate horizontal and vertical bounces.
Added an Aim & Shoot mechanic:
Move the mouse to choose the launch direction.
Only upward launch angles are allowed.
First click locks the aim.
Second click launches the ball.
Introduced Enchanted Power Dots that spawn randomly. Touching one activates a 2× score multiplier for 7 seconds.

Converted the game into an Endless Mode. Clearing all bricks no longer ends the game; it continues until all lives are lost.
Added Easy, Medium, and Hard difficulty modes that dynamically adjust:
Paddle width
Ball speed
Brick density/spawn behavior
Number of lives
Completely redesigned the game's visuals:
Added a custom star-themed background.
Precisely fitted the game canvas inside a polaroid-style frame.
Refreshed the color palette using a warm cream, yellow, orange, and deep plum theme for a cleaner and more cohesive look.
also changed the fonts. 

Power Dots and random brick spawning only activate after the ball is launched for the first time, keeping the aiming phase distraction-free.
Improved the endless gameplay by making random brick respawns continuous throughout the match with increased spawn frequency, larger spawn batches, and a higher maximum brick density.
