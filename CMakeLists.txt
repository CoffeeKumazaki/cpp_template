## Use the variable PROJECT_NAME for changing the target name
set( PROJECT_NAME "random_generator_iterator" )

cmake_minimum_required(VERSION 3.1)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
project(${PROJECT_NAME})

## Define libraries
#add_library(${PROJECT_NAME}_lib
# 
#)

## Define the executable
set(SRCS 
  main.cpp
)
add_executable(${PROJECT_NAME} ${SRCS})