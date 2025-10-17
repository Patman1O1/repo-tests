cmake_minimum_required(VERSION 3.5...4.1)
project(libstatic LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)

add_library(libstatic STATIC libstatic.cpp)
