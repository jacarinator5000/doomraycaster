cmake_minimum_required(VERSION 3.5.0)
project(doomraycaster VERSION 0.1.0 LANGUAGES C CXX)

add_library(doomraycaster doomraycaster.cpp)

include(CTest)
enable_testing()

