cmake_minimum_required(VERSION 3.11)

project(Vehicle_driver_task VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(Uebungsprojekt
    src/Board.cpp
    src/Game.cpp
    src/Human.cpp
    src/Player.cpp
    src/Main.cpp

)

target_include_directories(Uebungsprojekt
    ${CMAKE_SOURCE_DIR}/inc
)