# CMake minimum version
cmake_minimum_required (VERSION 2.8)

# Project name
project (NetworkDemo)

# Excutable bin
add_executable(Server server.c)
add_executable(Client client.c)
