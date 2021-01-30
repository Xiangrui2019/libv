cmake_minimum_required(VERSION 3.17)
project(libv C)

set(CMAKE_C_STANDARD 11)

add_library(libv SHARED library.c library.h)