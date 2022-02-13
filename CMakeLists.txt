cmake_minimum_required(VERSION 3.21)
project(323_Protobuf_ModelCompany)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_EXE_LINKER_FLAGS "-static -static-libgcc")

add_executable(323_Protobuf_ModelCompany main.cpp)
