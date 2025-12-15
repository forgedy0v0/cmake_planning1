cmake_minimum_required(VERSION 4.2.0)
project(planning)
set(CMAKE_CXX_STANDARD 17)

set(EXECUTANLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
aux_source_directory(. SRC_LISTS)
add_executable(planning_main ${SRC_LISTS})