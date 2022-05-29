# advancecopter


## Copter project using advance navigation sensors and algorithms 


### Sensors

sensors | role | language | status | result | conclusion
-----|----------|----------|----------------|----------------------|-----------------------
m8n | posvel  |cpp | tested | working | conclusion
rplidar a1 | slam/proximity | ROS | tested | working | conclusion
realsense d415 | slam/proximity | Python | tested | working | conclusion




# Hardware

![alt text](https://github.com/pkr-7/advancecopter/blob/main/IMG_20220527_155558.jpg "BeagleBone Blue")


## Launch Scripts
1. rplidar a1(ROS): `roslaunch rplidar_ros rplidar.launch`, `roslaunch hector_slam_launch tutorial.launch` 
2. realsense d415: `python3 d4xx_to_mavlink.py`




## Test video
