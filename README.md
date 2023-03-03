# RACLAB_Turtlebot
RACLAB Turtlebot Waypoint Navigation <br>
Example Article [visit](https://core.ac.uk/download/pdf/387175328.pdf) <br>
Example amcl parameters [visit](https://github.com/firatbozkaya/RACLAB_Turtlebot_ws/blob/main/parameters_for_turtlebot_navigation.png) <br>


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
First for lidar > sudo chmod 777 /dev/tty*<br>
1 - roscore <br>
2 - rosrun waypoints waypoints_server <br>
3 - roslaunch rplidar_ros rplidar.launch <br>
4 - roslaunch turtlebot_navigation amcl_demo.launch map_file:='/home/raclab/raclab_ws/map4.yaml' <br>

-odom change odom2 for amcl with gmapping
# RACLAB [visit](https://raclab.org) website <br>
