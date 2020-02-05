cmake_minimum_required(VERSION 3.10)
project(sdl2_tutorials)

set(CMAKE_CXX_STANDARD 14)

add_executable(hello_sdl hello_sdl.cpp)
target_link_libraries(hello_sdl SDL2)
