﻿# Value Define
set(CMAKE_WIN32_EXECUTABLE ON)
set(USER_PROJECT_NAME RiaLoader)

# Cpp Standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add Library
link_libraries(Rut RxHook)

# Current Project
project("${USER_PROJECT_NAME}")
add_executable(${USER_PROJECT_NAME} "RiaLoader.cpp")
