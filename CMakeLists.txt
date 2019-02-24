cmake_minimum_required(VERSION 3.13)
project(cppstdlib)

set(CMAKE_CXX_STANDARD 11)

add_executable(util_chrono1 util/chrono1.cpp)
add_executable(util_chrono2 util/chrono2.cpp)
add_executable(util_clock1 util/clock1.cpp)
add_executable(util_enableshared1 util/enableshared1.cpp)
add_executable(util_limits1 util/limits1.cpp)
add_executable(util_minmax1 util/minmax1.cpp)
add_executable(util_pair1 util/pair1.cpp)
add_executable(util_ratio1 util/ratio1.cpp)