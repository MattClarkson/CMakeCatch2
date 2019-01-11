CMakeCatch2
------------------

[![Build Status](https://travis-ci.com/MattClarkson/CMakeCatch2.svg?branch=master)](https://travis-ci.com/MattClarkson/CMakeCatch2)
[![Build Status](https://ci.appveyor.com/api/projects/status/5pm89ej732c1ekf0/branch/master)](https://ci.appveyor.com/project/MattClarkson/cmakecatch2)


Purpose
-------

This is a demo project to demonstrate a reasonable folder structure for [CMake](https://cmake.org/) based projects,
that use [CTest](https://cmake.org/) to run unit tests via [Catch](https://github.com/catchorg/Catch2).


Credits
-------

This project was developed as a teaching aid for UCL's ["Research Computing with C++"](http://rits.github-pages.ucl.ac.uk/research-computing-with-cpp/)
course developed by [Dr. James Hetherington](http://www.ucl.ac.uk/research-it-services/people/james)
and [Dr. Matt Clarkson](https://iris.ucl.ac.uk/iris/browse/profile?upi=MJCLA42).

Build Instructions
------------------

This project itself can be built if you just want to test it. In Linux terms that
would be:
``` cmake
git clone https://github.com/MattClarkson/CMakeCatch2
mkdir CMakeCatch2-Build
cd CMakeCatch2-Build
cmake ../CMakeCatch2
make
```
But ideally, you should use this as a template to create your own project. To do so,
please refer to the [CMakeTemplateRenamer](https://github.com/MattClarkson/CMakeTemplateRenamer)
which will show you how to clone this repository, and rename all the variables to names of your choice.
Then you would simply build your new project, using cmake, as shown above.
