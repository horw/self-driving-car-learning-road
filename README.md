[ROADMAP](https://sarrasor.github.io/RoboticsRoadmap/)


[Which language I need to choice to develop ROS Package](https://roboticsbackend.com/python-vs-cpp-with-ros/)
## Video
1. [Udacity Course](https://learn.udacity.com/courses/ud0419/lessons/)
2. [Apollo Course](https://github.com/ApolloAuto/apollo)
3. [Apollo Baidu Course](https://apollo.baidu.com/community/course/outline/)
4. [Bilibili Channel Course](https://www.bilibili.com/video/BV1mJ411R7Ni/?share_source=copy_web)
5. [ROS Docker Easy Publisher and Subscriber](https://www.youtube.com/watch?v=IDGtmcydio0)

## Books
1. [Brief introduction about ROS](http://docs.voltbro.ru/starting-ros/messaging/message.html)
2. [Docker+Python+ROS](https://github.com/ginomempin/sample-dockerized-ros2-node)
3. [AutoLabor](http://www.autolabor.com.cn)

## Helpfull links
1. [Command in ros docker with env](https://stackoverflow.com/questions/55941916/unable-to-execute-catkin-commands-using-run-in-dockerfile) 
2. [ROS Wiki](http://wiki.ros.org/)
3. [ROS Python Logger](https://github.com/ros/ros_comm/issues/1384)  **[solution 1](https://gist.github.com/nzjrs/8712011)** **[solution 2](https://docs.python-guide.org/writing/logging/)**
4. [ROS 2](https://docs.ros.org/en/humble/Tutorials)
5. [Video Tutorial about tf2, urdf...](https://articulatedrobotics.xyz/ready-for-ros-7-urdf/)

## Wiki
[catkin](http://wiki.ros.org/catkin/commands)

## Visialusation
[ros3djs](https://github.com/deltaautonomy/delta_viz)
[rosboard](https://github.com/dheera/rosboard)

## ROS package structure
- **include/package_name**: C++ include headers (make sure to export in the CMakeLists.txt)
- **msg/**: Folder containing Message (msg) types
- **src/package_name/**: Source files, especially Python source that are exported to other packages.
- **srv/**: Folder containing Service (srv) types
- **scripts/**: executable scripts
- **CMakeLists.txt**: CMake build file (see catkin/CMakeLists.txt)
- **package.xml**: Package catkin/package.xml
- **CHANGELOG.rst**: Many packages will define a changelog which can be automatically injected into binary packaging and into the wiki page for the package 
- [link](http://wiki.ros.org/Packages)

## ML
[reinforcement learning](https://pythonprogramming.net/introduction-reinforcement-learning-stable-baselines-3-tutorial/)
