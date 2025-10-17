cmake_minimum_required(VERSION 4.1)
project(libinterface)

set(CMAKE_CXX_STANDARD 23)

add_library(libinterface STATIC libinterface.cpp)
