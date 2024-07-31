cmake_minimum_required(VERSION 3.20)
set(CMAKE_LEGACY_CYGWIN_WIN32 OFF)

project(cpp_console_app_project CXX)

set(ARGPARSE_INCLUDE third_party/argparse/include)

add_executable(cpp_console_app "source/main.cpp")
set_property(TARGET cpp_console_app PROPERTY CXX_STANDARD 20)
target_include_directories(cpp_console_app PRIVATE ${ARGPARSE_INCLUDE})
