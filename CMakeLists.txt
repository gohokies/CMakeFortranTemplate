# 
# CMake options
# 

cmake_minimum_required(VERSION 3.9)

project(CMakeFortranTemplate Fortran)

# Output directories
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/bin)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/lib)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/lib)

# 
# Project directories
# 
add_subdirectory(src)
add_subdirectory(sample)