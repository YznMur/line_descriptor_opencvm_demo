Target
Since OpenCV3.4.6 and later versions remove the LSD line feature extraction algorithm from the code, this library extracts the separate LSD line feature extraction algorithm through the code extraction of the source code of OpenCV3.4.2 and OpenCV-Contrib3.4.2 and encapsulates it in in the cvm namespace.

How to use
First enter the line_descriptor_opencvm folder, then
```
mkdir build
cd build
cmake ..
make
```
After that, the header file and shared library file of the compiled LSD algorithm will be obtained, and then the main function can be compiled and run with cmake. The line feature extraction and matching results of the two images can be obtained.
