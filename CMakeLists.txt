cmake_minimum_required(VERSION 3.12)

project(cpp-types)

add_library(cpp-types INTERFACE)

target_include_directories(cpp-types INTERFACE "include")
target_compile_features(cpp-types INTERFACE cxx_std_20)