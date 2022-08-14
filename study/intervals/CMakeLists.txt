cmake_minimum_required(VERSION 3.10)
project(intervals)

add_executable(intervals main.cpp)
target_include_directories(intervals PRIVATE
    ../../renderdoc
    )
