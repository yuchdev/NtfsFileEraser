cmake_minimum_required(VERSION 3.0)
project(file_eraser C)
set(TARGET file_eraser)

file(GLOB SOURCES *.c *.h *.rc)
add_executable(${TARGET} ${SOURCES})
