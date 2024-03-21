cmake_minimum_required(VERSION 3.10.2)
project(moveit_resources_panda_six_circle_description)
find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY urdf DESTINATION share/${PROJECT_NAME})
