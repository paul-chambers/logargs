cmake_minimum_required(VERSION 3.16)
project(logargs C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable( logargs logargs.c )

install( TARGETS logargs RUNTIME
         DESTINATION /usr/bin )