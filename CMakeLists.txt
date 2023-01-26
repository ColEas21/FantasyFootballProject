cmake_minimum_required(VERSION 3.23)
project(fantasyFootballProject)

set(CMAKE_CXX_STANDARD 14)

add_executable(fantasyFootballProject main.cpp FantasyFootballTeam.cpp PlayerArrays.cpp FootballArt.cpp Round.cpp Ui.cpp Ui.h)
