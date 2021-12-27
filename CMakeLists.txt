cmake_minimum_required(VERSION 3.10)

project(PosiStageNet)

# Since this is a header-only library, 
# see http://mariobadr.com/creating-a-header-only-library-with-cmake.html
# and https://cmake.org/cmake/help/latest/command/add_library.html#interface-libraries

add_library(psn INTERFACE)
target_include_directories(psn INTERFACE include/)

add_subdirectory(examples/cmake)