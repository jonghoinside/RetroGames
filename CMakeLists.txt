cmake_minimum_required(VERSION 3.16)
project(RetroGames)

set(CMAKE_CXX_STANDARD 14)

add_executable(RetroGames
        Games/Arkanoid.cpp
        Games/Doodle_Jump.cpp
        Games/main.cpp
        Games/Minesweeper.cpp
        Games/Snake.cpp
        Games/Tron.cpp)
