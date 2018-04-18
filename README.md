FUNDAMENTALS OF COMPUTER GRAPHICS -  PROJECT REPORT

Author: Valentin KAO <valentin.kao@epitech.eu>
		张有请 - 2017280242
		
The purpose of this project is to implement an OpenGl program  

---------------------------------------------------------------------------
VIDEO CAPTURE
---------------------------------------------------------------------------

The video capture of my program named screenrecord.mp4, is available from
the root of the folder.

---------------------------------------------------------------------------
REQUIREMENTS
---------------------------------------------------------------------------
•	GCC 5 or later
•	CMake 3.9 or later
•	OpenGL, GLUT and SOIL libraries.
The code hasn't been tested on Windows but should work on Visual Studio
2015 and later.

---------------------------------------------------------------------------
BUILD AND USAGE
---------------------------------------------------------------------------
From the folder in which you found this report, please enter the following
command lines.
1.		mkdir build && cd build
2.		cmake ..
3.		make

Once the compilated was successful, you can execute the program. 
Here is the usage of the program.

	./SnowStorm [--width=x] [--height=y] [--title=”Assignment”]
	
---------------------------------------------------------------------------
FLAGS – OPTIONS	DESCRIPTION	DEFAULT
---------------------------------------------------------------------------
width, w	Set the width of the window	900
height, h	Set the height of the window	900
title, t	Set the title of the window	“Assignment 2”


---------------------------------------------------------------------------
SOFTWARE DESIGN
---------------------------------------------------------------------------
In order to implement future project easily, I define a simple application
design. Those three classes are singletons avoiding any multiple instances.

Application class is in charge of parsing the arguments and to init the
graphical core of the program with the input window size or the input
window name. 

GraphicalCore initializes OpenGL engine : window creation, keyboard handler,
mouse handler, reshape handler, etc.

Engine is the core of the project : 

---------------------------------------------------------------------------
ALGORITHM IMPLEMENTED
---------------------------------------------------------------------------

---------------------------------------------------------------------------
FUNCTIONNALITIES
---------------------------------------------------------------------------
By pressing the key ESC, you close the program properly.