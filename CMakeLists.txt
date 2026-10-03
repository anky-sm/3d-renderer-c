cmake_minimum_required(VERSION 4.4)
project(3drenderer C)

set(CMAKE_C_STANDARD 99)

add_executable(3drenderer src/main.c)
add_compile_options(-Wall)