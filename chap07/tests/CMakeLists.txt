cmake_minimum_required(VERSION 3.16)

project(my-logging-lib VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

add_executable(first_test "")

target_sources(first_test PRIVATE
  Creation.cpp
  Confirm.cpp
  Setup.cpp
  main.cpp
)
