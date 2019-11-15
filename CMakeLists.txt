cmake_minimum_required(VERSION 3.13)
project(PE_ePWM)
set(CMAKE_CXX_STANDARD 14)

file(GLOB SOURCES "src/*.c" "src/*.h")

add_library(PE_ePWM ${SOURCES})