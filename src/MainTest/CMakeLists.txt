﻿# Value Define
set(USER_PROJECT_NAME MainTest)

# Cpp Standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add Library
link_libraries(Rut RxUI)

# Current Project
project("${USER_PROJECT_NAME}")
add_executable(${USER_PROJECT_NAME} "main.cpp")

