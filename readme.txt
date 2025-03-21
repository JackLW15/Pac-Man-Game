Problem satement: Build a working pacman game. The game must be built using tiles, so no messing with pictures for the background. Nothing can move diagnol. So pacman and the ghost must move either up, down, left, or right. Atleast one ghost must use A* algorthim to hunt down pacman. 


Ghost and the pathfinding

so each ghost is different 
first up is pincky. Pincky will move right or left at the first chance, but only goes up and down once a collision with a wall occurs.
inky is the same way as pincky but insead of left and right, inky will go up and down. and only moves left or right once a collision with a wall occurs.
Clyde will move up, down, left and right at every chance possible. I did this because I was wondering which would be better. Clyde or blinky.

Clyde, Inky and Pincky path finding works as the following. if pacmans cords are greater then the ghost at the given point then the ghost will take the first chance possible to make their cords to match pacman.

Blincky is using A* path finding. This does not work because I still have trouble understanding on how to implement the algorthm into my program.


The A* algorthim is using the heuristic Manhattan..

To play the pacman I have prested you need to find the small little green dot. This is pacman. the movements are self expantory. To win you must clear the board of all dots. You lose once the ghost have caught you four times. Once you have cleared the board you have beaten the game

The drawlings of Pac-Man was done by me. I messed up the scale of Pac-Man, but because I thought it was funny I kept it.
