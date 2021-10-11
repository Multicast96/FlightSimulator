# CMakeList.txt : CMake project for CoreApi, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("CoreApi")

# Add source to this project's executable.
add_executable (CoreApi "src/CoreApi.cpp" "src/CoreApi.h")

# TODO: Add tests and install targets if needed.
