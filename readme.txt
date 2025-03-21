Problem satement: Build a working pacman game. The game must be built using tiles, so no messing with pictures for the background. Nothing can move diagnol. So pacman and the ghost must move either up, down, left, or right. Atleast one ghost must use A* algorthim to hunt down pacman. 

Ok so the video i have attached is the same one that I showed during class. I am showing thi video because my A* is breaking my code to the point i can't run the program.
I am not sure what I have done wrong and I can't figure out so I am submitting what i got.

Ghost and the pathfinding

so each ghost is different 
first up is pincky. Pincky will move right or left at the first chance, but only goes up and down once a collision with a wall occurs.
inky is the same way as pincky but insead of left and right, inky will go up and down. and only moves left or right once a collision with a wall occurs.
Clyde will move up, down, left and right at every chance possible. I did this because I was wondering which would be better. Clyde or blinky.

Clyde, Inky and Pincky path finding works as the following. if pacmans cords are greater then the ghost at the given point then the ghost will take the first chance possible to make their cords to match pacman.

Blincky is using A* path finding. This does not work because my program claims the method call does not exist. which I know it does. Because of this Blincky won't move and the program can't run. So i have includes some code to make Blincky only go in a direction once he hitts a wall. it's not random but it's simply just in another direction

A* time complexity is O(N^2) but if you don't like this answer please except this on O(N!)

The A* algorthim is using the heuristic Manhattan. I honest don't understand it I just had a turtial to help me implament it.

To play the pacman I have prested you need to find the small little green dot. This is pacman. the movements are self expantory. To win you must clear the board of all dots. You lose once the ghost have caught you four times. Once you have cleared the board you have beaten the game

Something I did do is I drew all of the ghost and pacman them self. From the death eyes to the scared ghost.


Why doesn't pacman use Twitter?     He doesn't like being followed
What would pacman do if he had legs?    he would walk-a-walk-a-walk-a-walk-a-walk-a-walk
