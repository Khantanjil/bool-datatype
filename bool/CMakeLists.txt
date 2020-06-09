cmake_minimum_required(VERSION 2.6)
project(allinone)

add_executable(allinone main.cpp)

install(TARGETS allinone RUNTIME DESTINATION bin)
