# GMapping for RPLIDAR
This is a turtlebot_navigation ROS package that uses GMapping algorithm for Simultaneous Localization and Mapping. However, the default 
parameters for the algorithm are designed for long range laser sensors such as Kinect Camera. The parameters are modified for RPLIDAR to 
generate a cleaner and accurate map. The parameters are located at
SPARbot/turtlebot_navigation/launch/includes/gmapping.launch

## Map generated BEFORE modifying the parameters
![alt tag](https://github.com/SPARbot/turtlebot_navigation/blob/master/before_mod.png)

## Map generated AFTER modifiying the parameters
![alt tag](https://github.com/SPARbot/turtlebot_navigation/blob/master/after_mod.png)


