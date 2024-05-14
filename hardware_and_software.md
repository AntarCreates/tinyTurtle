<p align="center">
<img src="https://github.com/AntarCreates/tinyTurtle/assets/81281780/c3ee4a0b-57a0-4a2e-9aae-60bfbf3fbdd2 height="250" width="600"/>


</p>

# 1. Hardware Requirements:
There are no specific restrictions on what the hardware components should be. You could use them as per your preference and availability. As for my case, I used the following:

1. **Chassis:** [3D printable chassis](https://github.com/AntarCreates/tinyTurtle/tree/main/meshes)
2. **Drives:** N20 Micro Metal Gear DC Motors with 2 Phase Magnetic Encoders x2 with wheels
   
Motor Specs:

![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/3a657389-978a-4571-a515-60cd77d58f63)

Wheel Specs:

![image](https://github.com/AntarCreates/tinyTurtle/assets/81281780/6d56d104-7016-4662-8c61-087d0165e640)


4. **Motor Driver:** L298n H-Bridge motor driver x1
5. **Micro-controllers:**
    -  ESP32- CAM x1, and/or
    -  ESP32 DEVKIT V1 38 Pins x1
6. **Power Supply:** 11.1 V 1100 mAh Li-Po battery x1
7. **Peripherals-**
   - 55 mm M3 nuts and bolts x8
    - Lots of jumper cables (>x20)
    - Electrical cable ties/zip ties x10

After initial setup mine looked like this [PS. That' my cat, Finster. he likes to sleep on the table]
|CAD|Real|
|---|---|
|<img src="https://github.com/AntarCreates/tinyTurtle/assets/81281780/5c01d682-0607-49cc-be0c-d35fd1b9ffeb" width="500" height="600"/>|<img src="https://github.com/AntarCreates/tinyTurtle/assets/81281780/52588d59-b812-4544-9b9f-97a509bab553" width="400" height="600"/>|

# 1. Software Requirements:
Again, no restrictions here. Here are the things that I am currently using:
1. [ROS2 Iron](https://docs.ros.org/en/iron/index.html) running on an Ubuntu 22.04 system
2. [ArduinoIDE](https://www.arduino.cc/en/software) or
3. [PlatformIO](https://platformio.org/install/ide?install=vscode) setup on a VSCode environment
4. [Micro-ROS](https://micro.ros.org/)
5. [EdgeImpulse Studio](https://edgeimpulse.com/) for tinyML pipeline
