Set up in Ubuntu 24.04 with ros2 jazzy

Steps to follow (assuming opt/jazzy/install/setup.bash is sourced):
mkdir ros2_ws
cd ros2_ws
mkdir src
git clone
cd ..
colcon build
source install/setup.bash
ros2 launch robot_description view_robot.launch.py
