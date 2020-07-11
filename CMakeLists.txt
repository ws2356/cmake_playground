cmake_minimum_required(VERSION 3.14.0)

project(cmake_playground)

set(cmake_playground_dir ${CMAKE_CURRENT_SOURCE_DIR})
message(STATUS "cmake_playground_dir: ${cmake_playground_dir}")

get_filename_component(cmake_playground_parent_dir ${cmake_playground_dir} DIRECTORY)
message(STATUS "cmake_playground_parent_dir: ${cmake_playground_parent_dir}")