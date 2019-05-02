# ICanteen
Install guide and User guide for ICanteen 

/////////////////////////////////////////
Install guide
////////////////////////////////////////
The install guide has been made as simplistic as possible from the creators of kivi. This installation guide will be for windows 10 devices only. 

First step is to install python 3.7.3 from: https://www.python.org/downloads/ 

Once python is installed follow these steps or visit: https://kivy.org/doc/stable/installation/installation-windows.html

1. Ensure you have the latest pip and wheel:

  python -m pip install --upgrade pip wheel setuptools

Install the dependencies (skip gstreamer (~120MB) if not needed, see Kivy’s dependencies):

  python -m pip install docutils pygments pypiwin32 kivy.deps.sdl2 kivy.deps.glew
  python -m pip install kivy.deps.gstreamer
Note:
If you encounter a MemoryError while installing, add after pip install an option –no-cache-dir.

For Python 3.5+, you can also use the angle backend instead of glew. This can be installed with:

  python -m pip install kivy.deps.angle
Install kivy:

  python -m pip install kivy

You should be fully operational now!!!

///////////////////////////////////////
User Guide
//////////////////////////////////////
