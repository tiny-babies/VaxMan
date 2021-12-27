### Edit of hbokmann's Pacman into "VaxMan"

The new goal of this game is to vaccinate all the ghosts who have Covid.  Every 30 seconds, the ghosts will spread Covid (duplicate), and if the unvaccinated ghost count reaches 32 or over, then it is game over.  

I changed nearly aspect of the game's implementation.  I made the ghosts' movement around the map to be smarter when colliding with the walls so that the ghosts know to change directions once they come into contact with a wall.  To make this implementation better, I also changed the map around so that it would be more fun for the player to navigate the map, and the ghosts could more easily move around the map.

The original python script also had confusing or poorly-coded logic in some areas, so I went ahead and simplified.  

The original version of this Pacman game is here: 

https://github.com/hbokmann/Pacman/
