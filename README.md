# GraphicsProjects

## Assignment 1

This assignment was to use python and moderngl to create a window that would 
flash random colors in the corresponding window that was created


## Assignment 2

This assignment was to use moderngl in python to create a triangle using vertcie positions
and then thrwoing them into a vertex shader which would compute the positions then draw them on the screen
creating a triangle after moving them through the fragment shader which will color the needed verticies in white

![screenshot](Assignment2/Assignment%202%20output%20Remi%20Roper.png)


## Assignment 3

This assignment was to use the graphical equations to plot out the points to make out a heart through creating 
vertex points for each point. Then it was to take those points and color them magenta within the fragment shader.
in the graphical loop of the program we were then to feed in a scale factor in order to make the plotted shape 
to oscilate size from big to small.

![screenshot](Assignment3/Assignment%203%20output%20Remi%20Roper.png)


## Assignment 4

This assignment was to create a object loader that would compute the bounds and vertex data used to load the object
onto the screen from a .obj file starting witht the first object the teapot. You as the user would then be able to 
select between keyboard 1-6 in order to see the given object rotate in 3D space. All of which would be colored by
the fragment shader to be colored by the normals of the object.

![screenshot](Assignment4/Screenshot%202024-09-15%20213450.png)


## Assignment 5

Very Similar to the previous assignment, all that was changed here was the perspective of the camera which had changed 
from a regular view to a birds eye view looking down on all of the objects.

![screenshot](Assignment5/Screenshot%202024-09-23%20152453.png)


## Assignment 6

This assignment took a change in that instead of one object at a time there is a now a floor object and 100 teapots
in diffrent locations rotations and scales. After all this is done  the camera is rotated around the scene.


## Assignment 7

In this one I had learned more about point and directional lighting and attempted to create a scene of a teapot and 
the flooring with directional or point lighting depending on the users input of pressing l.


## Assignment 8

Assignment 8 started to make this a little more intresting by adding textures to the objects having the grass texture
for the ground and a gold texture for the teapot. After implementing this we made sure the lighting calculation was kept
so everything still looks correct with the given lighting.


## Assignment 9

For this Assignment, We took what we had in assignment 8 and furthered it by adding  reflection of a skybox into the teapot
as we also created a skybox for the assigment and giving the scene the correct lighting.


## Project 1

For project one it was have basically the same render as assignment 8 but instead we are creating a shadow with the use of 
of directional and point lighting. showing they have diffrent shadows depending on the lighting used.


## Project 2

For project two it was have basically the same render as assignment 8 but to then calculate the shadow by using a shadow map 
in a 2 step rendering process. First being the first render without shadow then create a shadow map with this map we can map 
the shadows onto the next and fianl render.

## Project 3

For this final project it was set up to be like the first project but witht the addition of normal maps. This addition would 
create some depth on the 3d objects being renderd when given the two normal maps so  that we are looking at something more 
intresting.