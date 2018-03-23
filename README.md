[![Build Status](https://travis-ci.org/NYUGeometricModeling/GM_Assignment_4.svg?branch=master)](https://travis-ci.org/NYUGeometricModeling/GM_Assignment_4)
# Assignment 4: Mesh Parameterization

This repository contains the viewer/painting code and data files you'll need for
assignment 4. General guideline will be the same as before. Link to [Handouts](https://cs.nyu.edu/~panozzo/gp18/Handout4.pdf) and [Slides](https://cs.nyu.edu/~panozzo/gp18/Assignment4.pdf) **Due on Apr 11, 2018 at 23:59EST.**



## Notice: Please Update to the newest version of libigl
There had been some change in libigl which makes previous assignments not compatible. However, starting from this one, you can use the latest master version of libigl, and of course, you don't need to change the lines in `.travis.yml`

There are two major changes:
* igl::viewer::Viewer -> igl::opengl::glfw::Viewer
* `nanogui` is replaced by `imgui`. Please see [here](https://github.com/libigl/libigl/blob/master/tutorial/tutorial.md#viewermenu) for more detail. You don't need menu in this assignment.

