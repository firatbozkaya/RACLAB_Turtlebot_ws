# RACLAB_Turtlebot
RACLAB Turtlebot Waypoint Navigation

# First Steps
install steps [visit](https://github.com/firatbozkaya/Turtlebot2-On-Melodic_raclab)
# Gmapping Doc
 [visit](http://wiki.ros.org/turtlebot_navigation/Tutorials/Build%20a%20map%20with%20SLAM)
# For Waypoint Dep
1 - cd raclab_ws/src <br>
2 - git clone https://github.com/firatbozkaya/waypoints_raclab.git
<br>
3 - cd ..
<br>
4 - catkin_make




# Navigation Code Steps <br>
1 - roscore <br>
2 - rosrun waypoint waypoint_server <br>
3 - roslaunch rplidar_ros rplidar.launch <br>
4 - roslaunch turtlebot_navigation amcl_demo.launch map_file:='~/raclab_ws/map4.yaml' <br>

# RACLAB [visit](https://raclab.org) website <br>
