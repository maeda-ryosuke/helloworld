cmake_minimum_required(VERSION 3.16)
project(hello)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

add_executable(${PROJECT_NAME} src/helloworld.cpp)

target_link_libraries(${PROJECT_NAME})

