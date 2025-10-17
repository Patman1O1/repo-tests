cmake_minimum_required(VERSION 4.1)
project(libshared)

set(CMAKE_CXX_STANDARD 23)

add_library(libshared SHARED libshared.cpp)
