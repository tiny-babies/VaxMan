### Edit of hbokmann's Pacman into "VaxMan"

### Done with Pygame

The new goal of this game is to vaccinate all the ghosts who have Covid.  Every 30 seconds, the ghosts will spread Covid (duplicate), and if the unvaccinated ghost count reaches 32 or over, then it is game over.  

I changed nearly aspect of the game's implementation.  I made the ghosts' movement around the map to be smarter when colliding with the walls so that the ghosts know to change directions once they come into contact with a wall.  This was important to reduce the clustering of ghosts when the amount of ghosts are scaled to a large number.  The old implementation did not effectively deal with the scalability, leaving the ghosts to cluster together with similar movements when they duplicate.  To make this implementation better, I also changed the map around so that it would be more fun for the player to navigate the map, and the ghosts could more easily move around the map.

The original python script also had confusing or poorly-coded logic in some areas, so I went ahead and simplified.  

The original version of this Pacman game is here: 

https://github.com/hbokmann/Pacman/

![image](https://user-images.githubusercontent.com/91104605/154907911-c621400b-da7e-4d53-b98c-f822643d8571.png)
![image](https://user-images.githubusercontent.com/91104605/154908077-aacee132-af07-47cc-87db-410e711b5d73.png)
![image](https://user-images.githubusercontent.com/91104605/154908116-9121da32-1e09-4829-91bf-548c14ebddd0.png)



