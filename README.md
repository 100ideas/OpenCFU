OpenCFU
======

What is OpenCFU
-------
OpenCFU is a `C++` program to count bacterial colonies and other circular objects.
It heavily uses `OpenCV` for image processing and `Gtkmm` for GUI.
More information is available http://www.opencfu.sourceforge.net.
For a more technical description, you can read the article published 
on PLoS ONE (http://tinyurl.com/o3bk24o).

Installation
-------
http://opencfu.sourceforge.net/devcorner.php

Building on Mac OS X
-------
The brew dependencies are likely overkill.

	brew tap homebrew/science
	brew install pkg-config autoconf automake glibmm libtool opencv 
	git clone https://github.com/kitschpatrol/OpenCFU.git
	cd opencfu
	autoreconf -i
	./configure --without-gui 
	make
