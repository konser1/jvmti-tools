cmake_minimum_required(VERSION 3.29)
project(faketime)
include_directories(D:/jdk-11/include)
include_directories(D:/jdk-11/include/win32)
set(CMAKE_CXX_STANDARD 20)

add_library(faketime SHARED
        faketime.cpp)
