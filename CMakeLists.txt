cmake_minimum_required(VERSION 3.15)
project(GESPP)

set(CMAKE_CXX_STANDARD 23)
file(GLOB SOURCES src/*.cpp)
add_executable(GESPP ${SOURCES} main.cpp)