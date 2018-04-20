cmake_minimum_required(VERSION 2.6)
project(rodcutproblem)

add_executable(rodcutproblem main.cpp)

install(TARGETS rodcutproblem RUNTIME DESTINATION bin)
