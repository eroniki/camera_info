cmake_minimum_required(VERSION 2.8.3)
project(camera_info)

## Find catkin macros and libraries
find_package(catkin REQUIRED COMPONENTS roscpp rospy std_msgs image_transport cv_bridge rqt_gui_py)
find_package(OpenCV)

## Declare catkin package
catkin_package()

## Specify additional locations of header files
include_directories(${catkin_INCLUDE_DIRS})
