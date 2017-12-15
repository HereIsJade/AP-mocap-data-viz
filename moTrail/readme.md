This is a 3D scatter plot rendered using webGL using on mobile phone accelerometer data.  You can change view by rotating cube using the mouse.  At present there's no relationship between the colours of the particles.

The visualisation uses the fantastic [threejs library](http://threejs.org/) for the 3D and hooks into webGL.  The example presented here is heavily based on the threejs scatter plot example.  I've also used [d3.js](http://d3js.org/) for some of convenience functions to import the data, scale the data and set up the ranges for the axis's.

The motion trail is printed through 3 trail currently.
The Heartrate data is combined with the color of dots, The higher of heartrate the higher of Red value of dots. 


you have to have the open the file in the local server enviroment or through the virture machine 