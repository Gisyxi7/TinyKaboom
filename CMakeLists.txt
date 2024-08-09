cmake_minimum_required(VERSION 3.27)
project(Kaboom)

set(CMAKE_CXX_STANDARD 17)



add_executable(Kaboom main.cpp
        include/geometry.h)


add_executable(Kaboom_gif gif.cpp)
