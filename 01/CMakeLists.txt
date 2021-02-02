cmake_minimum_required(VERSION 2.8.12)
project(learnopengl)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(learnopengl01 learnopengl01.cpp)
target_link_libraries(learnopengl01 ${CONAN_LIBS})
