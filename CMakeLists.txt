cmake_minimum_required(VERSION 3.15)
project(tarea2)

file(GLOB SOURCE
        "src/*"
        )

add_executable(tarea2 ${SOURCE})