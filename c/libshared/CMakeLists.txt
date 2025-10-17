cmake_minimum_required(VERSION 4.1)
project(libshared C)

set(CMAKE_C_STANDARD 23)

add_library(libshared SHARED libshared.c)
