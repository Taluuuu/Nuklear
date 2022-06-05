cmake_minimum_required(VERSION 3.18)
project(nuklear)

add_library(nuklear nuklear.c)
target_include_directories(nuklear PUBLIC ./)