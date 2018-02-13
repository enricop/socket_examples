cmake_minimum_required(VERSION 2.8)

project(sockets)
#add_executable(${PROJECT_NAME} "main.cpp")

add_executable(ServerSelect "server_select.cpp")
add_executable(ServerPoll "server_poll.cpp")

add_executable(ReceiveMulticast "receive_multicast.cpp")

add_executable(AcceptorHandlerASIO "acceptor_handler_asio.cpp")
