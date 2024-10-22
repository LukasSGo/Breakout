# Breakout

W Kavanagh. June Summer 2024

## controls

A/D to move the paddle right and left.
P to pause.

## Powerups

big/small paddle (blue)
fast/slow ball (fancy yellow)
fire ball (green)

# Tasklist

## Suggested fixes

* Fix the compiler issues in the code

## Suggested tasks

* Implement mouse input for pad
* Improved VFX (ball trail, paddle hit response, brick particle destruction)
* Better UI (progress bar rather than timer for countdown).
* GameLoop
* Better ball physics (Box2D)
* Leaderboards
* More ball types (e.g., multiball, sticky ball [where you shoot the ball from the paddle every time], tiny ball, big ball, brick-tracking ball)
* Sounds with increasing tone between bounces.
* Implement commentary with calls to an LLM such as LLama

# Time Details and Changelist
<Add information to this section about the time you've taken for this task along with a professional changelist.>

Compiler Issue Fixed: 15 mins~
Removed the include that was placed incorrectly in the power up base .h class.

Big Ball Power Up: 45 mins~
Power up that makes the ball smaller is added to the power up pool

Small Ball Power Up: 30 mins~
Power up that makes the ball bigger is added to the power up pool

Game Loop Created: 40 mins~
The game now loops back to the begining after winning or losing.

Camera Shake: 45 mins~
The camera now shakes when you lose a life


