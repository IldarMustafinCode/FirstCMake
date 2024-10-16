cmake_minimum_required(VERSION 3.5.0)
project(firstCM VERSION 0.1.0 LANGUAGES C CXX)

add_executable(firstCM main.cpp)


#
if(WIN64)
    message(STATUS "Building for Windows")
endif()

message("a;b;c")