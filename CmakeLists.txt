cmake_minimum_required(VERSION 3.10)

project(for_oop)

set(CMAKE_CXX_STANDARD 17)

include_directories(src)

set(SOURCES
    src/main.cpp
    src/utils.cpp
)

add_executable(for_oop ${SOURCES})