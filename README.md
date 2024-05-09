# ROS2 Koch curve Project

This ROS 2 Turtlesim project is designed to generate the Koch curve.

## Prerequirements
- ROS 2
- turtlesim package

## Usage
### Ensure you have ROS 2 and turtlesim installed.
1. Clone this repository:
```bash 
git clone https://github.com/LazlowHUN/ros2_feleves.git ~/your/ros2/workspace
```
2. Modify setup.py
```py
'turtlesim_controller = ros2_course.turtlesim_controller:main'
```
3. On the terminal navigate to your workspace directory
```bash
cd /your_directory/ros2/workspace
```
4. Build the package:
```bash
colcon build --symlink-install
```
5. Run the turtlesim node:
```bash
ros2 run turtlesim turtlesim_node
```
6. In a new terminal, run the controller:
```bash
ros2 run /your_directory/ros2/workspace turtlesim_controller
```
