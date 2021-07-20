cmake_minimum_required(VERSION 3.1)
project(arithmetic-svc)

include_directories(/opt/restbed/include /opt/rapidjson/include ${CMAKE_BINARY_DIR})
link_directories(/opt/restbed/library)
add_executable(arithmetic-svc Main.cpp)
