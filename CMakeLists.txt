cmake_minimum_required(VERSION 3.15)
project(mpm LANGUAGES C CXX CUDA)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_BUILD_TYPE RELEASE)
set(CUDA_PATH /usr/local/cuda)
set(CMAKE_CUDA_ARCHITECTURES 89)

add_subdirectory(mpm)
