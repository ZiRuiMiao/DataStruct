cmake_minimum_required(VERSION 3.17)
project(Vesion_C C)

set(CMAKE_C_STANDARD 11)

add_executable(Vesion_C main.c SqlList/SqlList.c SqlList/SqlList.h SqlList/TestSqlList.c)