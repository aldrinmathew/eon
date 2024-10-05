cmake_minimum_required(3.24.0)
project(eon
  VERSION "1.0.0"
  DESCRIPTION "Electropunk Object Notation"
  HOMEPAGE_URL "https://github.com/aldrinmathew/eon.git")

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "-std=c++20 -fuse-ld=lld")

add_executable("eon" main.cc)
