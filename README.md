EECS373
LAB4
Junkai Wang
jxw875



There are 7 files in lab4_package on my GitHub which are the launch file, urdf file, xcaro file, urdf_from_xcaro file, config file, CMakeLists and package.xml. The launch file can launch the robot in rviz with the GUI. Also, if I enter “rosparam set /use_gui true” and “rosrun joint_state_publisher joint_state_publisher” in new terminal” in new terminal after we run robot.launch. The robot in rviz can also be enabled and we can see the move of the wheels. Furthermore, we have the urdf file and xcaro file on the GitHub. Xcaro file contains wheel joints which have type continuous. Urdf_from_xacro file is the file converted from xcaro file I wrote. Finally, when I run robot.launch, it initialize the config file. Config file has all of the data of the robot I built followed lab instructions.
