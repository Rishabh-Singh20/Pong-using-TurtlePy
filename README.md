Pong game created using TurtlePy. 

Ball.Py controls the movement of the ball, like when it reaches any of the horizontal border then it should bounce off of it.
If the ball hits the paddle then it should bounce as well but if it reaches beyond the paddle then the ball comes back to the 
center of the board and goes towards the other direction from the direction it previously started. After every successful hit 
off of the paddle, the speed of the ball increases.

Paddle.Py controls the movement of both of the paddles. They are allowed to move only vertically using the keys mentioned.

Scoreboard.Py is responsible for updating the scoreboard. Whenever the ball reaches beyond either of the paddle, the opposite
player gets a point. 

Main.Py is responsible for the working of the entire game by calling each class in each file at the time they have to be called.
