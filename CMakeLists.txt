cmake_minimum_required(VERSION 2.6)
project("G")

add_definitions("-std=c++11")

set(SRC src/main.cpp)

add_executable(pacwoman ${SRC})

target_link_libraries( pacwoman sfml-sfml)
target_link_libraries( pacwoman sfml-window)
target_link_libraries( pacwoman sfml-graphics)
target_link_libraries( pacwoman sfml-audio)
target_link_libraries( pacwoman sfml-network)