# [Project2: Toolbox Functions](https://github.com/CIS700-Procedural-Graphics/Project2-Toolbox-Functions)
This project is a procedurally modeled and animated wing. I started by creating a bezier curve and spawning feathers along this curve. 

I animated the wing by using a sin wave that took in time as a parameter and rotating it along the z axis. 
I did a similar action on the x and y directions based on the wind to create a small vibration. You can probably see the vibration if you look at the upper right hand feathers. 

I controlled the orientation and size of the feathers with a bias function. I also varied the color using a bias function as well. A user can change the base color of the feathers as well as the curvature, size, orientation, and animation.

If you actually drag along the sliders, the program glitches, but if you just click on a new location to update a value, it should work fine.

![alt tag](https://raw.githubusercontent.com/emily-vo/Project2-Toolbox-Functions/master/bluewing.png)
![alt tag](https://raw.githubusercontent.com/emily-vo/Project2-Toolbox-Functions/master/greenwing.png)
![alt tag](https://raw.githubusercontent.com/emily-vo/Project2-Toolbox-Functions/master/pinkwing.png)