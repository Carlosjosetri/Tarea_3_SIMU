cmake_minimum_required(VERSION 3.14)
project(_TSC_Laboratorio3_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(_TSC_Laboratorio3_master
        problem.msh
        classes.h
        display_tools.h
        LICENSE
        main.cpp
        math_tools.h
        sel.h
        TareaLaboratorio3.pdf
        tools.h)
