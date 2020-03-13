cmake_minimum_required(VERSION 2.8.3)
project(pixel_aggregation_network)

find_package(catkin)

catkin_python_setup()

catkin_package(
  LIBRARIES pixel_aggregation_network
)

install(
  PROGRAMS
    
  DESTINATION
    ${CATKIN_PACKAGE_BIN_DESTINATION}
)