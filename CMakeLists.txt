cmake_minimum_required(VERSION 3.23)

project(NumberGuess LANGUAGES CXX)

add_executable(NumberGuess)
target_sources(NumberGuess 
    PRIVATE 
        src/main.cpp
)