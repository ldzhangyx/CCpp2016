cmake_minimum_required(VERSION 3.4)
project(inventory)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp readline.cpp)
add_executable(inventory ${SOURCE_FILES})