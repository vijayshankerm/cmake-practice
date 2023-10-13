cmake_minimum_required(VERSION 3.13.4)
project(VijayLearnsCMake)
add_executable(${PROJECT_NAME} main.cpp)
install(TARGETS ${PROJECT_NAME} RUNTIME DESTINATION bin)