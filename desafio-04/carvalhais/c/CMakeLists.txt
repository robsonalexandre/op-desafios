cmake_minimum_required(VERSION 3.10)

# set the project name
project(d04-c)

# add the executable
add_executable(chess chess.c)

# specify the C standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED True)

