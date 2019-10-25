cmake_minimum_required(VERSION 3.0.0)
project(step_2)

set(step_2_VERSION_MAJOR 1)
set(step_2_VERSION_MINOR 0)

configure_file(
  "${PROJECT_SOURCE_DIR}/step_2_config.hpp.in"
  "${PROJECT_SOURCE_DIR}/step_2_config.hpp"
  )

include_directories("${PROJECT_SOURCE_DIR}")

add_executable(step_2 step_2.cpp)
