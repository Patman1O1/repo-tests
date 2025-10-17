cmake_minimum_required(VERSION 4.1)
project(libstatic C)

set(CMAKE_C_STANDARD 23)

add_library(libstatic STATIC libstatic.c)
