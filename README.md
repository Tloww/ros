# ros Task



## Task Overview
-In this task, we installed ROS2 Humble on Ubuntu MATE (running inside VirtualBox), installed the Turtlesim package, ran the simulator, and controlled the turtle using the keyboard. Finally, we documented the process and prepared it for GitHub

## Installing Turtlesim

1. **Install the Turtlesim package**  
   (sudo apt install ros-humble-turtlesim)

## Check that Turtlesim is installed
   (ros2 pkg executables turtlesim)
    **Expected output includes**
- turtlesim draw_square
- turtlesim mimic
- turtlesim turtle_teleop_key
- turtlesim turtlesim_node

## Running Turtlesim
  **We need two terminals to run Turtlesim properly**

- Terminal 1: Start the simulator
 (source /opt/ros/humble/setup.bash
ros2 run turtlesim turtlesim_node)

- Terminal 2: Control the turtle
 (source /opt/ros/humble/setup.bash
ros2 run turtlesim turtle_teleop_key)

##  Result
- The Turtlesim window opens with a small turtle in the center.

- Using the keyboard arrows, the turtle moves and draws lines on the screen.

- Pressing Q will quit the simulation.

- This confirms that ROS2 Humble and Turtlesim are installed and working correctly.
   
## Screenshot
![Turtlesim Screenshot](https://github.com/Tloww/ros/blob/main/Screenshot%20at%202025-10-18%2023-12-36.png)


