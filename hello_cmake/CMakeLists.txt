# http://www.wakayama-u.ac.jp/~chen/cmake/cmakever.html
cmake_minimum_required (VERSION 2.8)

project (hello_cmake)

# The version number.
#set(PROG1_VERSION_MAJOR 1)
#set(PROG1_VERSION_MINOR 0)

#message("PROJECT_SOURCE_DIR=${PROJECT_SOURCE_DIR}")
#message("PROJECT_BINARY_DIR=${PROJECT_BINARY_DIR}")
# Make Prog4Config.h from Prog4Config.h.in and CMakeLists.txt
#configure_file("${PROJECT_SOURCE_DIR}/cmake/Prog1Config.h.in" "${PROJECT_BINARY_DIR}/Prog1Config.h")

# add the binary tree to the search path for include files
#include_directories("${PROJECT_BINARY_DIR}")
#
add_executable (hello_cmake src/main.cpp)
