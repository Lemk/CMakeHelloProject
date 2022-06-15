cmake_minimum_required(VERSION 3.2)
project(ConsoleHello LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23) #версія стандарта C++23 

add_executable( #загальний проект
	NewHello
	ConsoleNewStandart.cpp
)

add_executable( #додатковий проект
	NewHello_D
	ConsoleNewStandart.cpp
)