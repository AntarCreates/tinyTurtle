# 0. Bring up the robot in Gazebo
`ros2 launch tinyturtle_description gazebo.launch.py`

You shoudld see a similar interface [without the object infront of the camera] . The package comes preequiped with the differential drive and the camera plugin
![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/12fa3e85-ca64-48f2-826f-0d8925fec4df)

# 1. Drive the robot around in Gazebo environment
`ros2 run teleop_twist_keyboard teleop_twist_keyboard`
# 2. Visualize the robot in Rviz
`ros2 launch tinyturtle_description display.launch.py`
![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/ae2a60da-1430-4cb7-b6e3-0ec6adb72e36)

