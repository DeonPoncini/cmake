---
Title: cmake utilities
Description: cmake modules and useful utilities
Author: Deon Poncini

---

Cmake Utilities
===============

Developed by Deon Poncini <dex1337@gmail.com>

Downloads
---------
[github](https://github.com/DeonPoncini/cmake)

Installation
------------
    git clone https://github.com/DeonPoncini/cmake.git
    cd cmake
    mkdir _build
    cd _build
    cmake ..
    sudo make install

Usage
-----
To use the cmake modules, in your CMakeLists.txt:

    set(CMAKE_MODULE_PATH "${CMAKE_MODULE_PATH} ${CMAKE_INSTALL_PREFIX}/share/cmake/modules")

To use the include scripts, include them into your CMakeLists.txt:

    include("${CMAKE_INSTALL_PREFIX}/share/cmake/includes/Utils.cmake")

License
-------
Copyright (c) 2014 Deon Poncini. See the LICENSE file for license rights and limitations (MIT)
