cmake_minimum_required(VERSION 3.1)
project(clion_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp string.cpp)
add_executable(clion_test ${SOURCE_FILES})
target_link_libraries(clion_test bcosta_math)