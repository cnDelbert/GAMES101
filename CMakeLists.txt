cmake_minimum_required(VERSION 3.16)

set(CMAKE_CXX_STANDARD 20)

# Add PATH_WHERE_EIGEN3_INSTALLED to CMAKE_INSTALL_PREFIX
# THIS IS BAD CODE.
list(APPEND CMAKE_INSTALL_PREFIX "E:/Code/Graphics/GAMES101/")
include_directories(include)

add_subdirectory(hw0)
add_subdirectory(hw1)

project(GAMES101)