cmake_minimum_required(VERSION 3.16)
project(moveit_intro)

if(NOT TARGET gtest)
  add_subdirectory(/usr/src/googletest gtest)
  include(GoogleTest)
  include(CTest)
endif()
enable_testing()


add_subdirectory(robot_description)
