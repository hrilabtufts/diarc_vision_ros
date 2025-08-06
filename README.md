# diarc_vision_ros
ROS Service and Message definitions for interacting with DIARC VisionComponent via ROS

## Install (assumes an existing ROS install)
* Clone into your local ROS workspace
* Install ROS dependencies: ros-noetic-vision-msgs
* Build your ROS workspace (catkin_make)
* Be sure to source your ROS workspace. Ideally, just add it to your ~/.bashrc

NOTE: Be sure to rebuild your local diarcros_core after building diarc_vision_ros (i.e., ./gradlew buildAndPublishDiarcRos)
