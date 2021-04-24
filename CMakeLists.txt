cmake_minimum_required (VERSION 3.15)

set (CMAKE_CXX_STANDARD 11)

project (cpp_echo_server)

set (CMAKE_FLAGS ${CMAKE_FLAGS} "-Wall -g")

file (GLOB SRCS ./src/*.cc)

add_executable (${PROJECT_NAME} ${SRCS})




