cmake_minimum_required(VERSION 3.5)
project(mtexe)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c11")

add_executable(work work.c)
add_executable(fifo fifo.c)
add_executable(shell shell.c)
