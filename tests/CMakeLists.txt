cmake_minimum_required(VERSION 3.8)
project(InterviewTests)
set(CMAKE_CXX_STANDARD 17)
set(SOURCE_FILES
        main.cpp
        Test.cpp
        )
add_executable(InterviewTests ${SOURCE_FILES} )