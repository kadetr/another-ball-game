# another-ball-game
with Phaser

dx-ball like game with following items:

BASICS

ball: works with Phaser arcade physics. Every time it hits brick or paddle a hit counter increases. After reaching hit limit, ball gets fasters and counter restarts.

paddle: works with cursor keys.

brick: exists several types of bricks. up until now, soft, hard , invisible, explode and unbreakable.
- soft: 1 hit (bullet or ball)
- hard: 2 hits (bullet or ball)
- invisible: 3 hits (bullet or ball)
- explode: 1 hit (explodes and breaks adjacent bricks -up, down, left, right-
- unbreakable: only explode (not ball nor bullet can break it except explode brick)

level: keeps the level map and brick details in matrix 

POWERUPS

paddle can lenghten 
paddle can shorten
paddle can acquire a gun to shoot bricks
paddle can work inverse. (left key takes right, right key goes left)

ball can fasten
ball can slow down
ball can split up to 4

IN PROGRESS-FUTURE WORK

- creating +40 levels: classic dx-ball like levels as well as actual concepts (trump, corona, virus, social media, etc) 
- solving performance issues: I created a version without Phaser and it works pretty fast but also I want to create a version with Phaser with acceptable performance.
- start game with different types of balls/paddles
- level up to earn activate powerups
- refactoring the code for better memory and calculation performance 
