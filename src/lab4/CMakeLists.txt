cmake_minimum_required(VERSION 2.8.3)
project(lab4)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  message_generation
  moveit_ros_move_group
  moveit_ros_planning_interface
)

## Generate added messages and services
generate_messages(DEPENDENCIES std_msgs)


catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

add_executable(test1 src/test.cpp)
target_link_libraries(test1 ${catkin_LIBRARIES})
