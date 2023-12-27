cmake_minimum_required(VERSION 3.27)
project(praktikum_11_1_FH_Aachen_OperatorPointer_TEST)

set(CMAKE_CXX_STANDARD 17)

add_executable(praktikum_11_1_FH_Aachen_OperatorPointer_TEST main.cpp
        test_operator_MyRectangle.cpp
        test_MyRectangle.cpp
        test_MyCanvas.cpp
        MyCanvas.cpp
        MyRectangle.cpp)
