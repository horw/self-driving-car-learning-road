- **include/package_name**: C++ include headers (make sure to export in the CMakeLists.txt)
- **msg/**: Folder containing Message (msg) types
- **src/package_name/**: Source files, especially Python source that are exported to other packages.
- **srv/**: Folder containing Service (srv) types
- **scripts/**: executable scripts
- **CMakeLists.txt**: CMake build file (see catkin/CMakeLists.txt)
- **package.xml**: Package catkin/package.xml
- **CHANGELOG.rst**: Many packages will define a changelog which can be automatically injected into binary packaging and into the wiki page for the package 
- [link](http://wiki.ros.org/Packages)
