add_library(lib src/Calc.cpp)
message("${CMAKE_CURRENT_SOURCE_DIR} is the current source")
 
target_include_directories(lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)