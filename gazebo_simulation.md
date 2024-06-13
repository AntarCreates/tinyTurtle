<img src="https://github.com/AntarCreates/tinyTurtle/assets/81281780/41bc9c3d-be44-45c5-ac29-f5d034ce207d" height="450" />

## The Importance of Simulation Before Deploying Robots

1. **Risk Mitigation**: Testing in a simulated environment helps identify and rectify potential issues, reducing the risk of failure in real-world applications.
2. **Cost Efficiency**: Simulations save time and resources by minimizing the need for physical prototypes and trial-and-error processes.
3. **Performance Optimization**: Allows for fine-tuning and optimizing robot behavior and algorithms without the constraints and variability of physical testing.
4. **Safety Assurance**: Ensures that robots operate safely, preventing harm to humans, other machines, and the environment.

### How Gazebo and RViz Can Help

- **Gazebo**:
  - Provides a robust physics engine for realistic simulation of robot interactions with the environment.
  - Allows testing of sensors, algorithms, and robot models in a controlled, repeatable setting.
  - Supports complex scenarios and multi-robot simulations, enhancing the development process.

- **RViz**:
  - Offers real-time 3D visualization of robot states and sensor data.
  - Helps in debugging and understanding robot behavior by providing intuitive insights into what the robot perceives.
  - Integrates seamlessly with ROS (Robot Operating System), allowing for comprehensive system testing and visualization.


# 0. Bring up the robot in Gazebo
`ros2 launch tinyturtle_description gazebo.launch.py`

You shoudld see a similar interface [without the object infront of the camera] . The package comes preequiped with the differential drive and the camera plugin
![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/12fa3e85-ca64-48f2-826f-0d8925fec4df)

# 1. Drive the robot around in Gazebo environment
`ros2 run teleop_twist_keyboard teleop_twist_keyboard`
# 2. Visualize the robot in Rviz
`ros2 launch tinyturtle_description display.launch.py`
![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/ae2a60da-1430-4cb7-b6e3-0ec6adb72e36)

![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/503e82ed-0f98-4612-949b-59310509714b)
