cmake_minimum_required(VERSION 3.23)
project(Server)

set(CMAKE_CXX_STANDARD 14)

include_directories("Header Files")

add_executable(Server
        "Header Files/Class_Logger.hpp"
        "Header Files/Class_NetworkInit.hpp"
        "Header Files/Function_Menu.hpp"
        "Header Files/Function_MessageParser.hpp"
        "Header Files/Function_NetworkCom.hpp"
        "Header Files/Function_RunCounter.hpp"
        "Header Files/Library_IDManager.hpp"
        "Program Codes/ChatServer.cpp")
