# Raylib-Template-cmake
C++ (idk why theres 99% c)

This is a raylib template for anyone wanting to use raylib on windows (maybe eve mac but 100% sure)
(note: I have only tried this using vs code)

When configuring it will create a build file

First time compile and configuring will take a bit as it needs to download some dependencies. Which means I think,
Key word: 'think', you dont need to download raylib before hand

when it compiles it will compile the src (you can change this in the cmake lists around line 37)
and will also copy the res folder into the build directory (you can delete this by going to the cmake file and
deleting line 46 - "file(COPY "${CMAKE_CURRENT_SOURCE_DIR}/res" DESTINATION ${CMAKE_CURRENT_BINARY_DIR})")

you can change the exe name at line 2 by changin 'TemplateName'

the default example is a raylib window

Enjoy :D
