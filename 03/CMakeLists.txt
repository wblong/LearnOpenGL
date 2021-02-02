cmake_minimum_required(VERSION 2.8.12)
project(learnopengl)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(learnopengl03 learnopengl03.cpp)
target_link_libraries(learnopengl03 ${CONAN_LIBS})
