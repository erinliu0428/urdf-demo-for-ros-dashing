# urdf-demo-for-ros-dashing
A little urdf demo for ros dashing, include launch files for robot_state_publisher, joint_state_publisher and rviz2 . Just change the file road of urdf for your own road.

- build
$colcon build --symlink-install
- source
$source install/setup.bash
- launch
$ros2 launch testbot_description testurdf.launch.py
