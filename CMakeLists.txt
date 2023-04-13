cmake_minimum_required(VERSION 3.23)
project(Petrakova C)

set(CMAKE_C_STANDARD 11)

add_library(Petrakova library.c libs/data_structures/vector/vector.c libs/data_structures/vector/vector.h)
