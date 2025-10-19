# ros
## Task Overview
In this task, we installed ROS2 Humble on Ubuntu MATE (running inside VirtualBox), installed the Turtlesim package, ran the simulator, and controlled the turtle using the keyboard. Finally, we documented the process and prepared it for GitHub

##Installing Turtlesim
1-Install the turtlesim package
sudo apt install ros-humble-turtlesim
2-Check that turtlesim is installed
ros2 pkg executables turtlesim

Expected output shows the following executables:
turtlesim draw_square
turtlesim mimic
turtlesim turtle_teleop_key
turtlesim turtlesim_node

##Running Turtlesim
We need two terminals to run Turtlesim properly
Terminal 1: Start the simulator
source /opt/ros/humble/setup.bash
ros2 run turtlesim turtlesim_node
Terminal 2: Control the turtlesource /opt/ros/humble/setup.bash
ros2 run turtlesim turtle_teleop_key

##Result
The Turtlesim window opens with a small turtle in the center.
Using the keyboard arrows, the turtle moves and draws lines on the screen.
Other keys like Q can quit the simulation.
This confirms that ROS2 Humble and Turtlesim are installed and working correctly.

##Screenshot
![Turtlesim Screenshot](screenshot.png)
