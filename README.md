Set up in Ubuntu 24.04 with ros2 jazzy

Steps to follow (assuming opt/jazzy/install/setup.bash is sourced):
1) mkdir ros2_ws
2) cd ros2_ws
3) mkdir src
4) git clone https://github.com/MilindKharwade7/robot_arm_manip.git
5) cd ..
6) colcon build
7) source install/setup.bash
8) ros2 launch robot_description view_robot.launch.py
