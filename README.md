# ping-pong-java
this repo include the source coe of 2 player ping pong 2D game in java

Description:

Pong is an arcade game, in which two players control "paddles" and try to knock a ball back and forth. If the ball gets past your opponent's paddle, you get a point. Whoever gets the most points win.
The game is played by using the keyboard (one player plays using the arrow keys “up” and “down “and other one plays using the “w” and “s” keys). Players can move their paddles up and down on the screen, and when the ball hits the paddle it bounces off. The ball should also bounce off the floor and ceiling and will need to detect when it has gotten past a paddle. When one paddle misses the ball, the opponent gets the point. It keeps the track of the current score on the scoreboard and declare a winner with more score.

![Pong Java](https://user-images.githubusercontent.com/56690325/201481720-479b5b18-693c-4287-b559-879e29ef86d2.png)


Features:


Modules:

•	Jframe
For Graphical Interface Jframe class from java swing library will be used to make frames and the components on it.	

•	JPanel	
Panel are Displayed over the frame.

•	Player vs Player
If the user choses Player vs Player mode, then both paddles will be moved manually by two players.

•	Player vs Computer
If the user choses Player vs Computer mode, then the left paddle will be moveable by the user and the other paddle will move automatically to bounce the ball.

•	Move_Ball
The movement of the ball is continuous, whenever it hits the (paddle or upper/lower boundary) it bounces.

•	New_Ball
After a player scores a goal, the ball goes behind the boundary and disappears. The new ball will appear in the center at random position.


•	Paddles
Two paddles are moved by players on right and left, blocks the ball to go out of boundary. 

•	Check_Collision
This method will validate and make the respective response when the ball collides to another component.

•	Ball Speed 
This method will increase the velocity of the moving ball as time passes. If a goal is scored by either player, the speed will again come to the default speed.

•	Score 
This method will count and display the goals/points scored by the players separately.









