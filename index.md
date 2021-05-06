The interactive art visualizer turns 2D shapes drawn by the user (that's you!) with a mouse into 3D revolved shapes. When you run the progam, a draw window opens where the left mouse button can be pressed or held and dragged to draw on the screen. The slower the drawing is made, the more accurate the 3D-shape will come out.

<img src="introwindow.JPG" width="500" />  <img src="drawing.JPG" width="500" />

### How Does it Work?
Whatever you draw with your mouse on the draw window will be revolved around the x axis (top edge of the window) to create a beautiful 3D shape! If there are any holes/gaps in your drawing in the x-axis direction, they will be automatically filled in through linear interpolation to create a continuous curve. When there are multiple points with the same x-value the highest y-value will be used when revolving the shape. When you are done drawing and are ready to see the revolved version of your masterpiece, press the 
escape key, which will open up a color picking window. 

<img src="colorpick.JPG" width="500" />

From here, you can select from a variety of colors, and a beautiful shape is created!

<img src="revolved.JPG" width="500" />

To access our Interactive 3D Art program on GitHub, you can check out our [project repository here](https://github.com/olincollege/Interactive-Art-Visualizer).

## Installation
To be able to run our program, the following libraries must be installed.

OpenCV
```markdown
pip install opencv-python
```
NumPy
```markdown
pip install numpy
```
MatPlotLib
```markdown
pip install matplotlib
```
PySimpleGUI
```markdown
pip install pip install PySimpleGUI
```

The 'pip' command can be used in a command window to install the libraries. If there are issues with installing the libraries, try "python -m pip install (library name here)" instead.

To run the program, execute the `main.py file`. There are no necessary changes to run the code, other than installing the libraries.

## Creators
<img src="elias.jpg" width="150"/>\
<a href="https://www.linkedin.com/in/elias-wheatfall-3683721b8/">Elias Wheatfall</a>\
Olin College of Engineering 2024\
Mechanical Engineering

<img src="sydney.jpg" width="150"/>\
<a href="https://www.linkedin.com/in/sydney-chung-b08569195/">Sydney Chung</a>\
Olin College of Engineering 2024\
Engineering with Robotics
