cmake_minimum_required(VERSION 2.8.3)
project(iai_hsr_sim)

find_package(catkin REQUIRED COMPONENTS
  hsr_description
  robot_state_publisher
  tf2_ros)

catkin_package()
