cmake_minimum_required(VERSION 3.16)
project(threads_ALONE C)

set(CMAKE_C_STANDARD 99)

add_executable(synchronized counter_mutex.c mutex.c)

# another
add_executable(unsynchronized counter.c mutex.c)