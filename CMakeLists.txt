cmake_minimum_required(VERSION 3.10)
project(F-C-RPG)

set(CMAKE_CXX_STANDARD 17)
add_executable(f-c-rpg main.cpp)
target_include_directories(f-c-rpg PRIVATE "/usr/lib")
target_link_libraries(f-c-rpg ${CMAKE_SOURCE_DIR}/lib/libIrrlicht.so)