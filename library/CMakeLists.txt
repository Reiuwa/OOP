cmake_minimum_required(VERSION 3.30)
project(MathLibrary)

set(SOURCE_FILES
    src/math_helpers.cpp
)

add_library(Library ${SOURCE_FILES})

target_include_directories(Library PUBLIC include)
