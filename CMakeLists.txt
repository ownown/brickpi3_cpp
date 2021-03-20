cmake_minimum_required(VERSION 3.5)
project(BrickPi3 VERSION 1.0)

FILE(GLOB SRC_FILES *.cpp)
add_library(BrickPi3 SHARED ${SRC_FILES})
target_include_directories(BrickPi3 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
