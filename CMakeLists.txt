cmake_minimum_required(VERSION 3.13)
project(proj C)

set(CMAKE_C_STANDARD 99)

add_executable(proj main.c estado.h estado.c stack.c stack.h auxiliares.c auxiliares.h comandos.c comandos.h cmake-build-debug/bot.c cmake-build-debug/bot.h bot.c bot.h)