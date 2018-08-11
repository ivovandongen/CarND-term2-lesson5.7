cmake_minimum_required(VERSION 3.10)
project(CarND_term2_lesson5_7)

set(CMAKE_CXX_STANDARD 14)

include(deps/eigen.cmake)

add_executable(Kalman main.cpp)
target_link_libraries(Kalman Eigen)
