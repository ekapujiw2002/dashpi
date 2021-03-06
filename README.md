DashPi
==========

A Raspberry Pi connected to a GoPro analyzing traffic signs with openCV in C++. More information can be found under [lyinch.com](http://www.lyinch.com/ "Lyinch's World").

Project Files
----------
Only use the main.cpp and the files provided in /lib/. Every other c++ file is deprecated. Examples images can be found in /input/

Arguments
----------
-d 					: debugging mode
-i <image>			: image path

Changelog
----------

#### Dashpi v0.0.2

* Initialization added
* Boundary check added
* Reduced unnecessary array invocations in the AOI algorithm
* Changed button to close the application- ESC or 'c' now ends the program
* Argument support
* Debugging mod triggered with argument
* Image path read in with argument
* Image resolution is checked

#### Dashpi v0.0.1

* Combined several approaches
* Creation of Area of Interests
* Console output in colours
* Better threshold algorithm

#### Threshold v.0.0.4

* Updated the Logging function to v.0.3
* Included arguments
* Arguments read the image file
* Variables sizes adapted to reduce unnecessary memory usage
* Sorting Algorithm v.0.3

#### Threshold v.0.0.3

* Sorting algorithm fixed (v.0.2)
* Included the ability to highlight the POIs with lines

#### Threshold v.0.0.2

* version number included
* POI structure included
* POI sorting algorithm included, based on bubble sort
* better log messages
* new file structure and variable names
* commented source code
* added version numbers for functions to track changes easier
* logging function streams output to cout


ToDo
---------
- [x] Include images as arguments
- [x] Highlight the POIs
- [x] Introduce AOIs 
- [x] Change exit button
- [x] Project initialization
- [x] Boundary check
- [x] Argument support
- [x] Reduce unnecessary array requests
- [ ] Write the threshold algorithm as a class
- [ ] Improve debugging information
- [ ] Check if application crashed
- [ ] Better window sizes and positions
- [ ] Draw box around the signs

Don't forget to checkout my [blog](http://www.lyinch.com/ "Lyinch's World").
