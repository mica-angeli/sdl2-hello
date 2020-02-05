cmake_minimum_required(VERSION 3.10)
project(sdl2_hello)

set(CMAKE_CXX_STANDARD 14)

add_executable(sdl2_hello main.cpp)
target_link_libraries(sdl2_hello SDL2)
