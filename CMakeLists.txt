cmake_minimum_required(VERSION 3.1)

set(CMAKE_CONFIGURATION_TYPES Debug)

project(ogl2dr)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory( glfw )

add_subdirectory( glad )

add_library(ogl2dr ogl2dr.h ogl2dr.cpp)