# 2022 Game Jam submission:  DisarmSelfDestruct

Small puzzle game inspired by one of the Mass Effect mini-games.

Link to project: https://github.com/babysitterd/DisarmSelfDestruct/releases/tag/v1.0

![Screenshot from Mass Effect](https://raw.githubusercontent.com/babysitterd/DisarmSelfDestruct/main/inspiredby.png "Signal Tracking Quest")

# Team

 * babysitterd (levon.dev@gmail.com)

# Interpretation of Theme

The puzzle looks like a bunch of concentric *circles*, you have to crack the code layer by layer to get to the **round core and disarm the self destruct of the Rogue AI.

# Other Things You Want To Share

As you might guess I didn't have much time so the code quality is far from perfect :) But I'm really happy to chip in and take part. readability-function-cognitive-complexity was turned off just to make unit-tests work, other functions should be within the limit of 25. Wasn't properly tested on Windows but should work fine if the window is sized adequately. 

## Rules

Player have to guess the code to disarm the self destruct of the Rogue AI. Code is a sequence of directions that player must enter in the correct order (on every mistake you'll have to start over). Additionally player has to outrun a self-destruct timer to avoid the big bang!

Controlled with arrow keys.
