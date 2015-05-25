cmake_minimum_required(VERSION 3.2)
project(lodepng)

set(SOURCE_FILES lodepng.cpp lodepng.h)
add_library(lodepng ${SOURCE_FILES})
target_include_directories(lodepng PUBLIC .)
