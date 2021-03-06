NIST Statistical Tests Suite
================

The statistical tests are implemented in C++ with MATLAB interface. 
For further details see http://sites.google.com/site/cristeab/home/nist-2

Compilation instructions:
- create in the folder containing this file the build folder:

   mkdir build

- change the current folder to the created folder and issue the following commands:

   cd build

   cmake ..

Note that the GSL library and its headers must be installed, otherwhise the above command
will fail. The sources are configured to be compiled in 'Release' mode by default. In order to
compile in 'Debug' mode use:

   cmake .. -DCMAKE_BUILD_TYPE=Debug

- compile

   make

An executable 'statisticaltests' is created in the build folder.

- install (optionally)

   make install

- generate help (optionally)

   make help

A folder 'html' is created in the build folder. Open 'index.html' with your
favorite browser.
