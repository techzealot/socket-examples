cmake_minimum_required(VERSION 3.19)
project(socket_examples)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_C_STANDARD 11)
add_executable(socket_examples main.cpp cpp/select/select_server.cpp cpp/poll/poll_server.cpp cpp/epoll/epoll_server.cpp c/select/select_server.c cpp/epoll/epoll_client.cpp cpp/poll/poll_client.cpp cpp/select/select_client.cpp c/select/select_client.c c/poll/poll_client.c c/poll/poll_server.c c/epoll/epoll_client.c c/epoll/epoll_server.c)