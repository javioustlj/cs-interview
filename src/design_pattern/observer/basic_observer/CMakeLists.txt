cmake_minimum_required(VERSION 3.2)
project(computer-science-interview-design_pattern-Observer
        LANGUAGES CXX
        VERSION 0.1)


add_executable(basic_observer BasicObserverMain.cpp Observer.cpp Subject.cpp)
