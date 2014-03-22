cmake_minimum_required(VERSION 2.8)
project (cmake)

#############################
# Includes
############################
install(DIRECTORY includes DESTINATION share/cmake)

#############################
# Modules
############################
install(DIRECTORY modules DESTINATION share/cmake)
