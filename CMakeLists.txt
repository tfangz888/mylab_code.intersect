cmake_minimum_required(VERSION 3.16)
project(mylab_code_intersect LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(intersect intersect.cpp)
add_executable(merge merge.cpp)
add_executable(difference difference.cpp)
add_executable(unique unique.cpp)
add_executable(excellent excellent.cpp)
add_executable(worse worse.cpp)

# cmake -S . -B build
# cmake --build build
