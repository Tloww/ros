# ros Task



## Task Overview
-In this task, we installed ROS2 Humble on Ubuntu MATE (running inside VirtualBox), installed the Turtlesim package, ran the simulator, and controlled the turtle using the keyboard. Finally, we documented the process and prepared it for GitHub

## Installing Turtlesim

1. **Install the Turtlesim package**  
   ```bash
   sudo apt install ros-humble-turtlesim

##Check that Turtlesim is installed
ros2 pkg executables turtlesim

##Running Turtlesim
We need two terminals to run Turtlesim properly:
- Terminal 1: Start the simulator
source /opt/ros/humble/setup.bash
ros2 run turtlesim turtlesim_node
- Terminal 2: Control the turtle
  source /opt/ros/humble/setup.bash
  ros2 run turtlesim turtle_teleop_key

 ## Result
![Turtlesim Screenshot](screenshot.png)
