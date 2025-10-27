cmake_minimum_required(VERSION 3.5...4.0)
project(dependency_manager VERSION 0.4.1)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")
set(CMAKE_MODULE_PATH "${CMAKE_MODULE_PATH}" PARENT_SCOPE)
include(DependencyManager)
