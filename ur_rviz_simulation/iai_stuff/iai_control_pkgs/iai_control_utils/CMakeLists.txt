cmake_minimum_required(VERSION 2.8.3)
project(iai_control_utils)

find_package(catkin REQUIRED
  rospy
)

catkin_package()

catkin_python_setup()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
