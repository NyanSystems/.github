cmake_minimum_required(VERSION 3.26)
project(github C)

set(CMAKE_C_STANDARD 23)

add_library(github SHARED library.c)
