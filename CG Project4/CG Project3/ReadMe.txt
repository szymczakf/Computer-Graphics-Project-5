CG Project 5 Filip Szymczak
Vector Images + 3D Sphere with Phong Shading

To create new image, select the width and height and press "New".
To draw a line/circle/polygon/rectangle/capsule, select the appropriate tool in one toolbox
and the appropriate shape in the other toolbox.
The figure will be drawn using the selected color (default black) and thickness (default 1).
Line:
	Click on two points to draw a line between them.
Circle:
	Click once to set the center of the circle, then again to choose the radius.
Polygon:
	Click on as many points as you like to add them to the polygon
	(new lines will keep showing up)
	To finalize, click in the vicinity of the first point.
Rectangle:
	Click on two points to draw a rectangle
	(you specify two vertices opposite to eachother).
Capsule:
	Click on two points to set the length of the lines,
	then click again to set the radius of the circles.
All drawn figures will have the thickness chosen in the "Thickness" combobox.

To edit a line/circle/polygon/rectangle, select the appropriate tool in the toolbox.
While editing, one can change the color and the thickness of the figure by selecting new values.
Line:
	Click one of the ends of the line to begin editing.
	Once selected, left-click to make it the new position of the chosen end or
	right-click to move the entire line to the new position.
Circle:
	Click in the middle of the circle to select it.
	Once selected, left-click to choose a new radius or
	right-click to move the circle to the new position.
Polygon:
	Click one of the vertices to begin editing.
	Once selected, left-click to make it the new position of the chosen vertex or
	right-click to move the entire polygon to the new position.
Rectangle:
	Click near one of the vertices to begin.
	Once selected, left-click to make it the new position of the chosen vertex or
	right-click to move the entire rectangle to the new position.

To delete a line/circle/polygon/rectangle, select the appropriate tool in the toolbox.
Line:
	Click one of the ends of the line to delete the line.
Circle:
	Click in the middle of the circle to delete it.
Polygon:
	Click one of the vertices to delete the polygon.
Rectangle:
	Click one of the vertices to delete the rectangle.

To clip a line/polygon/rectangle (Liang-Barsky), select the appropriate tool in the toolbox.
The clipping part will be highlighted in red.
Line:
	Click one of the ends of the line, then two more times to specify the clipping rectangle.
Polygon:
	Click one of the vertices, then two more times to specify the clipping rectangle.
Rectangle:
	Click one of the vertices, then two more times to specify the clipping rectangle.

To fill a polygon/rectangle, select the appropriate tool in the toolbox.
Solid Color Filling:
	Choose the "S. Fill" option. The chosen shape will be filled with the currently chosen color.
Pattern Filling:
	First, load a pattern using the "Load Pattern" option.
	Choose the "P. Fill" option. The chosen pattern will fill the shape.

All unsupported tool combinations will produce an error message.

To turn Antialiasing on or off, click the "Antialiasing" button.

Click "Redraw" if you wish to redraw the stored figures.
Click "Clear" delete currently stored figures and make a new image.

Click "Save" to save the stored figures as a .txt file.
Click "Load" to load a .txt file representing the figures.


3D Sphere with Phong Shading

First, one has to generate the image bitmap with "New".
Then, the sphere will be created and displayed by pressing the "Calculate Sphere" button.
The "Camera" sliders are responsible for the position of the camera (the sphere is in the centre of the coordinate system).
The "Point light" sliders are responsible for the position of the white point light illuminating the sphere.
One can also change the attributes of the sphere by changing the values of n, m and r and clicking the "Recalculate Sphere" button.

All the coefficients for the shading as well as for the size of the sphere are available in code and commented properly for ease of use.
Search for a comment "3D Project" in order to find them more easily (region Project5).
Should one want to rotate the sphere, uncomment the specified parts in the function "CalcSphere".