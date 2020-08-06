# 2D-Breakout-Game-JavaScript



We're going to create a game called "2D Breakout" using JavaScript and HTML 5. 

In the 2D Breakout game, you need to break all the bricks using a bouncing ball, a ball that you need to prevent from leaving the game area using the paddle.

![Image of 2D Breakout game](https://e7.pngegg.com/pngimages/820/161/png-clipart-breakout-video-game-sprite-atari-sprite-game-angle.png)

I chose to split it into two parts.

In the first segment, code is implemented to draw the paddle and the ball and be able to control the paddle using the left and the right arrows on the keyboard,and  make the ball moves, and also implemented the collision detection logic, so when the ball hits a wall it must change the direction.

When the ball hit the paddle, the ball should go in a definite direction based on where the ball hit the paddle so the paddle won't act like a wall. which means you can determine where the ball goes when you hit it with the paddle.

In the second segement, we will implement the bricks in the game, add a collision detection function, when the ball hit a brick, the brick must disappear and then increment the player's score.

The player has 3 lives, when he loses a life, we reset the ball position and give him a chance to continue playing, when he loses all the 3 lives, it's a game over, we show him a game over message, and a "play again" button to play over.

To win the game, the player has to break all the bricks on each level, and he has to complete 7 levels, when he passes from a level to another, the number of bricks increases and also the speed of the ball.

Implemented some sounds in the game, and created a button for when you want to turn ON/OFF the sounds.



