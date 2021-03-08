RPLIDAR A1M8 ROS package
=====================================================================

ROS node and test application for RPLIDAR

Visit following Website for more details about RPLIDAR:

rplidar roswiki: http://wiki.ros.org/rplidar

[LD108_SLAMTEC_rplidar_datasheet_A1M8_v3.0_en.pdf](https://github.com/MoffKalast/rplidar_ros/files/6100645/LD108_SLAMTEC_rplidar_datasheet_A1M8_v3.0_en.pdf)

[LM108_SLAMTEC_rplidarkit_usermaunal_A1M8_v2.0_en.pdf](https://github.com/MoffKalast/rplidar_ros/files/6100648/LM108_SLAMTEC_rplidarkit_usermaunal_A1M8_v2.0_en.pdf)


How to build rplidar ros package
=====================================================================
    1) Clone this project to your catkin's workspace src folder
    2) Running catkin_make to build rplidarNode and rplidarNodeClient

How to run rplidar ros package
=====================================================================
There're two ways to run rplidar ros package

I. Run rplidar node and view in the rviz
------------------------------------------------------------
roslaunch rplidar_ros view_rplidar.launch

You should see rplidar's scan result in the rviz.

II. Run rplidar node and view using test application
------------------------------------------------------------
roslaunch rplidar_ros rplidar.launch

rosrun rplidar_ros rplidarNodeClient

You should see rplidar's scan result in the console

Notice: the different is serial_baudrate between A1/A2 and A3/S1

RPLidar frame
=====================================================================
RPLidar frame must be broadcasted according to picture shown in rplidar-frame.png
