# advancecopter


## Copter project using advance navigation sensors and algorithms 

### Primary computer

board | role | autopilot | status | result | conclusion
-----|----------|----------|----------------|----------------------|-----------------------
matekh743mini | flight  |Ardupilot | tested | working | flight successful
matekh743mini | flight  | Px4 | tested | not working | wait for stable


### Secondary computer

board | role | os | status | result | conclusion
-----|----------|----------|----------------|----------------------|-----------------------
up2pro | slam  |ubuntu | tested | working | flight successful


### Secondary Sensors

sensors | role | language | status | result | conclusion
-----|----------|----------|----------------|----------------------|-----------------------
rplidar a1 | hector slam | ROS | tested | working | good to go
rplidar a1 | cartographer slam/proximity | ROS | tested | not working | os related
realsense d415 | slam/proximity | Python | tested | working | flight successful

### Primary Sensors

sensors | role | autopilot | status | result | conclusion
-----|----------|----------|----------------|----------------------|-----------------------
matek m9n can | ap_periph  |Ardupilot | tested | working | good to go
r1f | receiver | Ardupilot | tested | working | flight successful
sik | radio | Ardupilot | tested | working | flight successful
PMW3901 & Lidar VL53L0X | opticalflow | Ardupilot | tested | working | good to go


# Hardware

![alt text](https://github.com/pkr-7/advancecopter/blob/main/IMG_20220527_155558.jpg "Copter")


## Launch Scripts
1. rplidar a1(ROS): `roslaunch rplidar_ros rplidar.launch`, `roslaunch hector_slam_launch tutorial.launch` 
2. realsense d415: `python3 d4xx_to_mavlink.py`




## Test video
