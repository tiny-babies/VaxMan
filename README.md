### Edit of hbokmann's Pacman into "VaxMan"

The new goal of this game is to vaccinate all the ghosts who have Covid.  Every 30 seconds, the ghosts will spread Covid (duplicate), and if the unvaccinated ghost count reaches 32 or over, then it is game over.  

I changed nearly aspect of the game's implementation.  I made the ghosts' movement around the map to be smarter when colliding with the walls so that the ghosts know to change directions once they come into contact with a wall.  To make this implementation better, I also changed the map around so that it would be more fun for the player to navigate the map, and the ghosts could more easily move around the map.

The original python script also had confusing or poorly-coded logic in some areas, so I went ahead and simplified.  

The original version of this Pacman game is here: 

https://github.com/hbokmann/Pacman/

###Pacman in Python with PyGame

This is a very minimal implementation of the Pacman game, having only one level and without ghosts strategy, not even with random movements (yes, the routes are programmed). However, we may improve this game in the future and everyone else interested can feel free to fork and contribute to this project.

Download installer from here: https://github.com/hbokmann/Pacman/blob/master/pacman.exe

![Pacman Game Window](https://raw.github.com/hbokmann/Pacman/master/images/pacman.jpg)


# Future development

* Fix Pacman's movement
* Ghosts moving algorithm and artificial intelligence
* Better design
* Better algorithm for the walls
* Additional levels?


Tested with [PyGame 1.9](http://pygame.org/ftp/pygame-1.9.2a0.win32-py3.2.msi ) and [Python 3.2 32bit](http://www.python.org/ftp/python/3.2.3/python-3.2.3.msi)


### Additional resources
* [Pac-Man Dossier - strategy of the ghosts movement](http://home.comcast.net/~jpittman2/pacman/pacmandossier.html)
* [HTML5 Pacman](http://arandomurl.com/2010/07/25/html5-pacman.html)
* [PyGame tutorials](http://programarcadegames.com/index.php?lang=en)
* [How To Write a Pacman Game in JavaScript](http://www.masswerk.at/JavaPac/pacman-howto.html)
* [Original Pacman game](http://originalpacman.com/)



### Support or Contact
Twitter: https://twitter.com/hbokmann
