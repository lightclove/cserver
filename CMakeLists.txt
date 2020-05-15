cmake_minimum_required(VERSION 3.13)
project(cserver C)

set(CMAKE_C_STANDARD 11)

add_executable(cserver socket_server.c socket_client.c)
