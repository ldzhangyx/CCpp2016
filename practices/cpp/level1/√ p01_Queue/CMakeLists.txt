cmake_minimum_required(VERSION 3.4)
project(p01_Queue)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp queue.cpp queue.h
    README.md)

add_executable(p01_Queue ${SOURCE_FILES})