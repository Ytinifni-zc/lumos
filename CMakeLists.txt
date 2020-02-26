cmake_minimum_required(VERSION 3.2)
project(lumos)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -O3 -g -fopenmp")

include_directories(${CMAKE_SOURCE_DIR})
add_subdirectory(examples)
add_subdirectory(tools)
