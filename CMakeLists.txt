cmake_minimum_required(VERSION 3.5)
project(myProject)

#include(FetchContent)
#FetchContent_Declare(lib 
#	URL ${CMAKE_CURRENT_SOURCE_DIR}/lib_jfrog.zip
#)
#FetchContent_MakeAvailable(lib)

add_subdirectory(lib)
add_subdirectory(app)